---
tip: fonksiyon
kod: "10.03.01-1"
arac: "[[Keşif Metraj]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kollektör hattı metrajını güncelle

> Kod `10.03.01-1` · Araç: [[Keşif Metraj]]

## Ne yapar
- Kollektör hattı metrajını güncelle
- Bağlı modül: MEP poz/mahal metrajı.

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
