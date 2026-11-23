---
tip: fonksiyon
kod: "15.04.02-1"
arac: "[[Revizyon Turu]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Revizyon notlarını maddele

> Kod `15.04.02-1` · Araç: [[Revizyon Turu]]

## Ne yapar
- Revizyon notlarını maddele
- Bağlı modül: Revizyon sayısı, not ve ek tur talebi.

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
