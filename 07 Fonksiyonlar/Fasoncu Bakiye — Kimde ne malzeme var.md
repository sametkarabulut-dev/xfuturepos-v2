---
tip: fonksiyon
kod: "13.06.04-1"
arac: "[[Fasoncu Bakiye]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kimde ne malzeme var

> Kod `13.06.04-1` · Araç: [[Fasoncu Bakiye]]

## Ne yapar
- Kimde ne malzeme var
- Bağlı modül: Fasoncuda kalan malzeme görünümü

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
