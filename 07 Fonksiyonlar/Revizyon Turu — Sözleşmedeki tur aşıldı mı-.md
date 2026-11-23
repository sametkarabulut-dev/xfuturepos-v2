---
tip: fonksiyon
kod: "15.04.02-2"
arac: "[[Revizyon Turu]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Sözleşmedeki tur aşıldı mı?

> Kod `15.04.02-2` · Araç: [[Revizyon Turu]]

## Ne yapar
- Sözleşmedeki tur aşıldı mı?
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
