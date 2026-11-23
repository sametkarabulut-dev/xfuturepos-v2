---
tip: fonksiyon
kod: "15.04.05-2"
arac: "[[Arşiv Dolabı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Proje arşivini özetle

> Kod `15.04.05-2` · Araç: [[Arşiv Dolabı]]

## Ne yapar
- Proje arşivini özetle
- Bağlı modül: Teslim arşivi ve lisanslı stok ayrımı.

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
