---
tip: fonksiyon
kod: "12.03.02-2"
arac: "[[Hat Seferi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Hat 3 ü kalkışa kapat

> Kod `12.03.02-2` · Araç: [[Hat Seferi]]

## Ne yapar
- Hat 3 ü kalkışa kapat
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
