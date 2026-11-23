---
tip: fonksiyon
kod: "13.05.01-2"
arac: "[[Lot İzle]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu satışın hammaddesi

> Kod `13.05.01-2` · Araç: [[Lot İzle]]

## Ne yapar
- Bu satışın hammaddesi
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
