---
tip: fonksiyon
kod: "10.07.03-2"
arac: "[[Seviye Hakediş]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Ödeme bekleyenler

> Kod `10.07.03-2` · Araç: [[Seviye Hakediş]]

## Ne yapar
- Ödeme bekleyenler
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
