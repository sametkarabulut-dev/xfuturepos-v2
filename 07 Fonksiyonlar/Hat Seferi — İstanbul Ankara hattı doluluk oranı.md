---
tip: fonksiyon
kod: "12.03.02-1"
arac: "[[Hat Seferi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# İstanbul Ankara hattı doluluk oranı

> Kod `12.03.02-1` · Araç: [[Hat Seferi]]

## Ne yapar
- İstanbul Ankara hattı doluluk oranı
- Bağlı modül: Hat aracı kalkış, doluluk ve varış ambarında aktarma.

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
