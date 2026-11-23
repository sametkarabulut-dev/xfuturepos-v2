---
tip: fonksiyon
kod: "10.00.03-1"
arac: "[[Metraj Hakediş]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Mart hakediş taslağını hazırla

> Kod `10.00.03-1` · Araç: [[Metraj Hakediş]]

## Ne yapar
- Mart hakediş taslağını hazırla
- Bağlı modül: Poz/metraj hakediş ve kesintiler; Muhasebe genişlemesi.

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
