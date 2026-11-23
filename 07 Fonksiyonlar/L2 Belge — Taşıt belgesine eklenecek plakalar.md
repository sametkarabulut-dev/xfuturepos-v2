---
tip: fonksiyon
kod: "12.02.02-2"
arac: "[[L2 Belge]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Taşıt belgesine eklenecek plakalar

> Kod `12.02.02-2` · Araç: [[L2 Belge]]

## Ne yapar
- Taşıt belgesine eklenecek plakalar
- Bağlı modül: L2 yetki ve taşıt belgesi takibi; U-ETDS L2 yükümlülüğü.

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
