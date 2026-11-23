---
tip: fonksiyon
kod: "12.01.02-2"
arac: "[[K1 Belge]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Taşıt kartı olmayan plakaları listele

> Kod `12.01.02-2` · Araç: [[K1 Belge]]

## Ne yapar
- Taşıt kartı olmayan plakaları listele
- Bağlı modül: K1 yetki belgesi ve eki taşıt kartı süre/uyarma takibi.

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
