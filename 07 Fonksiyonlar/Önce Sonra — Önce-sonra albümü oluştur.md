---
tip: fonksiyon
kod: "10.04.04-1"
arac: "[[Önce Sonra]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Önce-sonra albümü oluştur

> Kod `10.04.04-1` · Araç: [[Önce Sonra]]

## Ne yapar
- Önce-sonra albümü oluştur
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
