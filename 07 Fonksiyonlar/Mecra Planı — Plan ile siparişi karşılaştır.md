---
tip: fonksiyon
kod: "15.05.01-1"
arac: "[[Mecra Planı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Plan ile siparişi karşılaştır

> Kod `15.05.01-1` · Araç: [[Mecra Planı]]

## Ne yapar
- Plan ile siparişi karşılaştır
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
