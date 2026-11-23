---
tip: fonksiyon
kod: "12.01.02-1"
arac: "[[K1 Belge]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# K1 belgesi ne zaman bitiyor

> Kod `12.01.02-1` · Araç: [[K1 Belge]]

## Ne yapar
- K1 belgesi ne zaman bitiyor
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
