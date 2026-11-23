---
tip: fonksiyon
kod: "15.08.03-1"
arac: "[[Destek Kuyruğu]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Açık destekleri önceliklendir

> Kod `15.08.03-1` · Araç: [[Destek Kuyruğu]]

## Ne yapar
- Açık destekleri önceliklendir
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
