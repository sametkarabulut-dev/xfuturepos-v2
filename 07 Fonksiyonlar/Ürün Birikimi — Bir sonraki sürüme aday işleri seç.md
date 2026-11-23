---
tip: fonksiyon
kod: "15.08.02-1"
arac: "[[Ürün Birikimi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bir sonraki sürüme aday işleri seç

> Kod `15.08.02-1` · Araç: [[Ürün Birikimi]]

## Ne yapar
- Bir sonraki sürüme aday işleri seç
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
