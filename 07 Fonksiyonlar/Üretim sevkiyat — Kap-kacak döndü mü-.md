---
tip: fonksiyon
kod: "16.06.02-2"
arac: "[[Üretim sevkiyat]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kap-kacak döndü mü?

> Kod `16.06.02-2` · Araç: [[Üretim sevkiyat]]

## Ne yapar
- Kap-kacak döndü mü?
- Bağlı modül: Mutfak planı, taşıma, servis ekibi, kap-kacak dönüşü.

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
