---
tip: fonksiyon
kod: "16.01.03-1"
arac: "[[Mekân lisans]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Müzik yayın izni bitiş?

> Kod `16.01.03-1` · Araç: [[Mekân lisans]]

## Ne yapar
- Müzik yayın izni bitiş?
- Bağlı modül: UMK (MSF) + müzik yayın izni + işyeri ruhsatı son tarih takibi.

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
