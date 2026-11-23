---
tip: fonksiyon
kod: "16.06.02-1"
arac: "[[Üretim sevkiyat]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Cumartesi üretim planı

> Kod `16.06.02-1` · Araç: [[Üretim sevkiyat]]

## Ne yapar
- Cumartesi üretim planı
- Bağlı modül: Mutfak planı, taşıma, servis ekibi, kap-kacak dönüşü.

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
