---
tip: fonksiyon
kod: "13.01.05-1"
arac: "[[Revize Sipariş]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Sipariş 55 miktarı 80 yap

> Kod `13.01.05-1` · Araç: [[Revize Sipariş]]

## Ne yapar
- Sipariş 55 miktarı 80 yap
- Bağlı modül: Üretimde miktar/ölçü değişikliği onayı

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
