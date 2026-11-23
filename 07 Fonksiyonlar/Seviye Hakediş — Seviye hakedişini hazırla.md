---
tip: fonksiyon
kod: "10.07.03-1"
arac: "[[Seviye Hakediş]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Seviye hakedişini hazırla

> Kod `10.07.03-1` · Araç: [[Seviye Hakediş]]

## Ne yapar
- Seviye hakedişini hazırla
- Bağlı modül: Form-22 seviye hakedişi.

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
