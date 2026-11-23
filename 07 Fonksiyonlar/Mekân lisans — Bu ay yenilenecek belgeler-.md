---
tip: fonksiyon
kod: "16.01.03-2"
arac: "[[Mekân lisans]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu ay yenilenecek belgeler?

> Kod `16.01.03-2` · Araç: [[Mekân lisans]]

## Ne yapar
- Bu ay yenilenecek belgeler?
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
