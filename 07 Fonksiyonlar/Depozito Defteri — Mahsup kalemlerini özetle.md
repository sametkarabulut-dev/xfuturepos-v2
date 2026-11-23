---
tip: fonksiyon
kod: "09.02.05-2"
arac: "[[Depozito Defteri]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Mahsup kalemlerini özetle

> Kod `09.02.05-2` · Araç: [[Depozito Defteri]]

## Ne yapar
- Mahsup kalemlerini özetle
- Bağlı modül: Depozito alma, iade, mahsup ve belgelendirme.

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
