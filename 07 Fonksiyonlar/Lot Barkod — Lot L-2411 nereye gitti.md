---
tip: fonksiyon
kod: "13.02.02-2"
arac: "[[Lot Barkod]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Lot L-2411 nereye gitti

> Kod `13.02.02-2` · Araç: [[Lot Barkod]]

## Ne yapar
- Lot L-2411 nereye gitti
- Bağlı modül: Parti/lot kodu üretimi ve sevk bağlama

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
