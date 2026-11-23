---
tip: fonksiyon
kod: "13.04.01-1"
arac: "[[Proje BOM]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Proje P-12 BOM v3

> Kod `13.04.01-1` · Araç: [[Proje BOM]]

## Ne yapar
- Proje P-12 BOM v3
- Bağlı modül: Projeye özel reçete revizyonları

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
