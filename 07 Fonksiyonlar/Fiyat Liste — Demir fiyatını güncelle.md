---
tip: fonksiyon
kod: "10.05.04-1"
arac: "[[Fiyat Liste]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Demir fiyatını güncelle

> Kod `10.05.04-1` · Araç: [[Fiyat Liste]]

## Ne yapar
- Demir fiyatını güncelle
- Bağlı modül: Cari/şantiye fiyat.

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
