---
tip: fonksiyon
kod: "10.06.04-1"
arac: "[[Oda Tescil]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Büro tescil bitişini hatırlat

> Kod `10.06.04-1` · Araç: [[Oda Tescil]]

## Ne yapar
- Büro tescil bitişini hatırlat
- Bağlı modül: Büro tescil / UYDS hesap.

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
