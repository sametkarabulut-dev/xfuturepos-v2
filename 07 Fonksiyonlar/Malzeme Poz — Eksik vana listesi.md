---
tip: fonksiyon
kod: "10.03.03-2"
arac: "[[Malzeme Poz]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Eksik vana listesi

> Kod `10.03.03-2` · Araç: [[Malzeme Poz]]

## Ne yapar
- Eksik vana listesi
- Bağlı modül: Tesisat malzeme-poz eşlemesi.

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
