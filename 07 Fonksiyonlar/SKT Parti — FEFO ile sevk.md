---
tip: fonksiyon
kod: "13.05.02-2"
arac: "[[SKT Parti]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# FEFO ile sevk

> Kod `13.05.02-2` · Araç: [[SKT Parti]]

## Ne yapar
- FEFO ile sevk
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
