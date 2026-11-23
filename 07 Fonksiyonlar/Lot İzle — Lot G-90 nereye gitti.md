---
tip: fonksiyon
kod: "13.05.01-1"
arac: "[[Lot İzle]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Lot G-90 nereye gitti

> Kod `13.05.01-1` · Araç: [[Lot İzle]]

## Ne yapar
- Lot G-90 nereye gitti
- Bağlı modül: Girdi-üretim-satış one-up/one-down izlenebilirlik

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
