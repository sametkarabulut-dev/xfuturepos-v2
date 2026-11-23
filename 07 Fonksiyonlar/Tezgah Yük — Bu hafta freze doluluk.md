---
tip: fonksiyon
kod: "13.01.04-1"
arac: "[[Tezgah Yük]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu hafta freze doluluk

> Kod `13.01.04-1` · Araç: [[Tezgah Yük]]

## Ne yapar
- Bu hafta freze doluluk
- Bağlı modül: Basit yük görünümü; MES kapasite planı değil

## Kullanan alt dallar
```base
filters:
  and:
    - 'tip == "isletme"'
    - file.hasLink(this.file)
views:
  - type: table
    name: Kullanan alt dallar
```
