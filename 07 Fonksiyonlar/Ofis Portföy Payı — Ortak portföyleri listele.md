---
tip: fonksiyon
kod: "09.01.04-1"
arac: "[[Ofis Portföy Payı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Ortak portföyleri listele

> Kod `09.01.04-1` · Araç: [[Ofis Portföy Payı]]

## Ne yapar
- Ortak portföyleri listele
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
