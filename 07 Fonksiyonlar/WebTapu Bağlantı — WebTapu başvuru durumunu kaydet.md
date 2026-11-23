---
tip: fonksiyon
kod: "09.04.05-1"
arac: "[[WebTapu Bağlantı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# WebTapu başvuru durumunu kaydet

> Kod `09.04.05-1` · Araç: [[WebTapu Bağlantı]]

## Ne yapar
- WebTapu başvuru durumunu kaydet
- Bağlı modül: Değerleme uzmanı WebTapu başvuru/belge durumunun dosya bazlı takibi.

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
