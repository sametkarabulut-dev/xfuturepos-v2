---
tip: fonksiyon
kod: "10.01.02-1"
arac: "[[İş Programı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kaba inşaat bitişini kaydır

> Kod `10.01.02-1` · Araç: [[İş Programı]]

## Ne yapar
- Kaba inşaat bitişini kaydır
- Bağlı modül: Kilometre taşı ve gecikme.

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
