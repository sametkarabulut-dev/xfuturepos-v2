---
tip: fonksiyon
kod: "15.04.05-1"
arac: "[[Arşiv Dolabı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Lisansı belirsiz stokları bul

> Kod `15.04.05-1` · Araç: [[Arşiv Dolabı]]

## Ne yapar
- Lisansı belirsiz stokları bul
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
