---
tip: fonksiyon
kod: "15.05.02-1"
arac: "[[Sipariş Teyidi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Teyidi gelmeyen siparişleri listele

> Kod `15.05.02-1` · Araç: [[Sipariş Teyidi]]

## Ne yapar
- Teyidi gelmeyen siparişleri listele
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
