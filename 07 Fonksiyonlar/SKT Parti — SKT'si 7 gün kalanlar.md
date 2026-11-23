---
tip: fonksiyon
kod: "13.05.02-1"
arac: "[[SKT Parti]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# SKT'si 7 gün kalanlar

> Kod `13.05.02-1` · Araç: [[SKT Parti]]

## Ne yapar
- SKT'si 7 gün kalanlar
- Bağlı modül: SKT/TETT ve FEFO sevk

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
