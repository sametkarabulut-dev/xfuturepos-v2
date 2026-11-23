---
tip: fonksiyon
kod: "15.05.01-2"
arac: "[[Mecra Planı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu ayın mecra planını özetle

> Kod `15.05.01-2` · Araç: [[Mecra Planı]]

## Ne yapar
- Bu ayın mecra planını özetle
- Bağlı modül: Mecra, tarih ve bütçe kalemi planı.

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
