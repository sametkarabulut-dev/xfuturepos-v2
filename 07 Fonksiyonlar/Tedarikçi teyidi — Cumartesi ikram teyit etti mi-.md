---
tip: fonksiyon
kod: "16.00.03-1"
arac: "[[Tedarikçi teyidi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Cumartesi ikram teyit etti mi?

> Kod `16.00.03-1` · Araç: [[Tedarikçi teyidi]]

## Ne yapar
- Cumartesi ikram teyit etti mi?
- Bağlı modül: Kalem bazlı tedarikçi atama ve yazılı teyit durumu.

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
