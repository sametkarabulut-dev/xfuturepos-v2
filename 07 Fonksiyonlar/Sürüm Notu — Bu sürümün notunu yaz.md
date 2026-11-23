---
tip: fonksiyon
kod: "15.08.04-1"
arac: "[[Sürüm Notu]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu sürümün notunu yaz

> Kod `15.08.04-1` · Araç: [[Sürüm Notu]]

## Ne yapar
- Bu sürümün notunu yaz
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
