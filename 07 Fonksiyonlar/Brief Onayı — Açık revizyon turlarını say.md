---
tip: fonksiyon
kod: "15.00.03-2"
arac: "[[Brief Onayı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Açık revizyon turlarını say

> Kod `15.00.03-2` · Araç: [[Brief Onayı]]

## Ne yapar
- Açık revizyon turlarını say
- Bağlı modül: Brief, sürüm ve revizyon turu; müşteri onayı kuyruğu.

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
