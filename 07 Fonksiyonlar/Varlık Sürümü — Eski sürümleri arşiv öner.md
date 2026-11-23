---
tip: fonksiyon
kod: "15.04.01-2"
arac: "[[Varlık Sürümü]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Eski sürümleri arşiv öner

> Kod `15.04.01-2` · Araç: [[Varlık Sürümü]]

## Ne yapar
- Eski sürümleri arşiv öner
- Bağlı modül: Dosya sürümü, final ve müşteri klasörü.

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
