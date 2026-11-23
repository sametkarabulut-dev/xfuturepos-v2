---
tip: fonksiyon
kod: "09.01.04-2"
arac: "[[Ofis Portföy Payı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Paylaşım kuralını özetle

> Kod `09.01.04-2` · Araç: [[Ofis Portföy Payı]]

## Ne yapar
- Paylaşım kuralını özetle
- Bağlı modül: Şube/franchise arası portföy görünürlük ve komisyon paylaşım kuralları.

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
