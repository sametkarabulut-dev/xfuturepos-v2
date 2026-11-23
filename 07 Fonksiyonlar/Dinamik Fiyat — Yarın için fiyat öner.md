---
tip: fonksiyon
kod: "09.05.06-1"
arac: "[[Dinamik Fiyat]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yarın için fiyat öner

> Kod `09.05.06-1` · Araç: [[Dinamik Fiyat]]

## Ne yapar
- Yarın için fiyat öner
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
