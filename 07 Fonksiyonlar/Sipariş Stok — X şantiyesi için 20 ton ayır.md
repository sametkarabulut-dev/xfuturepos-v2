---
tip: fonksiyon
kod: "10.05.01-2"
arac: "[[Sipariş Stok]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# X şantiyesi için 20 ton ayır

> Kod `10.05.01-2` · Araç: [[Sipariş Stok]]

## Ne yapar
- X şantiyesi için 20 ton ayır
- Bağlı modül: Sipariş, depo, rezervasyon.

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
