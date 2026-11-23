---
tip: fonksiyon
kod: "10.03.02-1"
arac: "[[Test Devreye]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Isıtma basınç testini kaydet

> Kod `10.03.02-1` · Araç: [[Test Devreye]]

## Ne yapar
- Isıtma basınç testini kaydet
- Bağlı modül: Test ve devreye alma checklist.

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
