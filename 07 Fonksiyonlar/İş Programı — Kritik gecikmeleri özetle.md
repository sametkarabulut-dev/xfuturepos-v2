---
tip: fonksiyon
kod: "10.01.02-2"
arac: "[[İş Programı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kritik gecikmeleri özetle

> Kod `10.01.02-2` · Araç: [[İş Programı]]

## Ne yapar
- Kritik gecikmeleri özetle
- Bağlı modül: Kilometre taşı ve gecikme.

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
