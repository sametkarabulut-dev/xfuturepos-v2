---
tip: fonksiyon
kod: "16.00.02-2"
arac: "[[Kapora sözleşme]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kalan bakiyeyi hatırlat

> Kod `16.00.02-2` · Araç: [[Kapora sözleşme]]

## Ne yapar
- Kalan bakiyeyi hatırlat
- Bağlı modül: Opsiyon, kapora, kesinleşme, kalan bakiye ve iade kuralı.

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
