---
tip: fonksiyon
kod: "12.01.03-1"
arac: "[[Yol Masrafı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Sefer 12 ye 2500 TL mazot ekle

> Kod `12.01.03-1` · Araç: [[Yol Masrafı]]

## Ne yapar
- Sefer 12 ye 2500 TL mazot ekle
- Bağlı modül: Mazot, köprü, bekleme masraflarını sefere bağlayıp kârlılık taslağı üretir.

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
