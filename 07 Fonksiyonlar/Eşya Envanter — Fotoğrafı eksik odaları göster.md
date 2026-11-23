---
tip: fonksiyon
kod: "12.05.02-2"
arac: "[[Eşya Envanter]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Fotoğrafı eksik odaları göster

> Kod `12.05.02-2` · Araç: [[Eşya Envanter]]

## Ne yapar
- Fotoğrafı eksik odaları göster
- Bağlı modül: Oda bazlı eşya listesi, kırılgan ve demontaj notları.

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
