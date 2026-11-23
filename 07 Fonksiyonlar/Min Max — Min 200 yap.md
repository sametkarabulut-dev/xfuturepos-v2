---
tip: fonksiyon
kod: "13.02.03-2"
arac: "[[Min Max]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Min 200 yap

> Kod `13.02.03-2` · Araç: [[Min Max]]

## Ne yapar
- Min 200 yap
- Bağlı modül: Yeniden üretim tetik noktası

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
