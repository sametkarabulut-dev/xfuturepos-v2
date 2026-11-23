---
tip: fonksiyon
kod: "15.05.02-2"
arac: "[[Sipariş Teyidi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yayın teyidini eşle

> Kod `15.05.02-2` · Araç: [[Sipariş Teyidi]]

## Ne yapar
- Yayın teyidini eşle
- Bağlı modül: Sipariş ve yayın teyidi eşlemesi.

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
