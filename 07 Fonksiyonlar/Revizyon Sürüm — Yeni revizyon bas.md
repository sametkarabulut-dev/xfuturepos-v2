---
tip: fonksiyon
kod: "10.06.02-2"
arac: "[[Revizyon Sürüm]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yeni revizyon bas

> Kod `10.06.02-2` · Araç: [[Revizyon Sürüm]]

## Ne yapar
- Yeni revizyon bas
- Bağlı modül: Sürüm ve pafta farkı.

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
