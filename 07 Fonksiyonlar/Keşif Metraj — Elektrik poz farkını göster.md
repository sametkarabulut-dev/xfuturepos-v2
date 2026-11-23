---
tip: fonksiyon
kod: "10.03.01-2"
arac: "[[Keşif Metraj]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Elektrik poz farkını göster

> Kod `10.03.01-2` · Araç: [[Keşif Metraj]]

## Ne yapar
- Elektrik poz farkını göster
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
