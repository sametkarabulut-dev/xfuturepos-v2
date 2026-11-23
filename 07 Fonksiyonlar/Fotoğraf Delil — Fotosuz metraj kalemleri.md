---
tip: fonksiyon
kod: "10.02.05-2"
arac: "[[Fotoğraf Delil]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Fotosuz metraj kalemleri

> Kod `10.02.05-2` · Araç: [[Fotoğraf Delil]]

## Ne yapar
- Fotosuz metraj kalemleri
- Bağlı modül: İmalat foto+konum.

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
