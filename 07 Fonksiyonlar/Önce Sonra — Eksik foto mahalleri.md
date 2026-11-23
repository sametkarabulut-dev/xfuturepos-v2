---
tip: fonksiyon
kod: "10.04.04-2"
arac: "[[Önce Sonra]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Eksik foto mahalleri

> Kod `10.04.04-2` · Araç: [[Önce Sonra]]

## Ne yapar
- Eksik foto mahalleri
- Bağlı modül: Mahal foto arşivi.

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
