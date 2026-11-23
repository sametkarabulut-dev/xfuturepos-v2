---
tip: fonksiyon
kod: "10.03.02-2"
arac: "[[Test Devreye]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Açık testleri listele

> Kod `10.03.02-2` · Araç: [[Test Devreye]]

## Ne yapar
- Açık testleri listele
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
