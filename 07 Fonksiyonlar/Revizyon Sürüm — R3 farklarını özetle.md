---
tip: fonksiyon
kod: "10.06.02-1"
arac: "[[Revizyon Sürüm]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# R3 farklarını özetle

> Kod `10.06.02-1` · Araç: [[Revizyon Sürüm]]

## Ne yapar
- R3 farklarını özetle
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
