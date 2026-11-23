---
tip: fonksiyon
kod: "15.08.02-2"
arac: "[[Ürün Birikimi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Destekten ürüne çevrilecekleri bul

> Kod `15.08.02-2` · Araç: [[Ürün Birikimi]]

## Ne yapar
- Destekten ürüne çevrilecekleri bul
- Bağlı modül: Ürün backlog ve sürüm hedefi.

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
