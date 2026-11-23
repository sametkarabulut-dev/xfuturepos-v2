---
tip: fonksiyon
kod: "10.02.05-1"
arac: "[[Fotoğraf Delil]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bugünkü imalat fotoğraflarını ekle

> Kod `10.02.05-1` · Araç: [[Fotoğraf Delil]]

## Ne yapar
- Bugünkü imalat fotoğraflarını ekle
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
