---
tip: fonksiyon
kod: "15.08.04-2"
arac: "[[Sürüm Notu]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kırıcı değişiklikleri işaretle

> Kod `15.08.04-2` · Araç: [[Sürüm Notu]]

## Ne yapar
- Kırıcı değişiklikleri işaretle
- Bağlı modül: Sürüm notu taslağı.

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
