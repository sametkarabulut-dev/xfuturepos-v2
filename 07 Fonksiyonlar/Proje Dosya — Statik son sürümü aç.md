---
tip: fonksiyon
kod: "10.06.01-1"
arac: "[[Proje Dosya]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Statik son sürümü aç

> Kod `10.06.01-1` · Araç: [[Proje Dosya]]

## Ne yapar
- Statik son sürümü aç
- Bağlı modül: Disiplin dosya ağacı.

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
