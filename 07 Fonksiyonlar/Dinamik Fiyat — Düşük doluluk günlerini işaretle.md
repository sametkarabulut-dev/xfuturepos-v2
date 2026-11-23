---
tip: fonksiyon
kod: "09.05.06-2"
arac: "[[Dinamik Fiyat]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Düşük doluluk günlerini işaretle

> Kod `09.05.06-2` · Araç: [[Dinamik Fiyat]]

## Ne yapar
- Düşük doluluk günlerini işaretle
- Bağlı modül: Sezon ve doluluk bazlı fiyat bandı önerisi; yazma insan onaylı.

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
