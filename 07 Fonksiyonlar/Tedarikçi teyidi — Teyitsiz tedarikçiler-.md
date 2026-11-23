---
tip: fonksiyon
kod: "16.00.03-2"
arac: "[[Tedarikçi teyidi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Teyitsiz tedarikçiler?

> Kod `16.00.03-2` · Araç: [[Tedarikçi teyidi]]

## Ne yapar
- Teyitsiz tedarikçiler?
- Bağlı modül: Kalem bazlı tedarikçi atama ve yazılı teyit durumu.

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
