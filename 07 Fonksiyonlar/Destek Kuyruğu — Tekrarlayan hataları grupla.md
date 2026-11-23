---
tip: fonksiyon
kod: "15.08.03-2"
arac: "[[Destek Kuyruğu]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Tekrarlayan hataları grupla

> Kod `15.08.03-2` · Araç: [[Destek Kuyruğu]]

## Ne yapar
- Tekrarlayan hataları grupla
- Bağlı modül: Ürün destek ticket'ı; proje kabul döngüsü değildir.

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
