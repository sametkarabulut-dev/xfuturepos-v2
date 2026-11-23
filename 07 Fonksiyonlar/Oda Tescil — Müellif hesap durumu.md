---
tip: fonksiyon
kod: "10.06.04-2"
arac: "[[Oda Tescil]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Müellif hesap durumu

> Kod `10.06.04-2` · Araç: [[Oda Tescil]]

## Ne yapar
- Müellif hesap durumu
- Bağlı modül: Büro tescil / UYDS hesap.

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
