---
tip: fonksiyon
kod: "10.05.01-1"
arac: "[[Sipariş Stok]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Çimento stoğunu söyle

> Kod `10.05.01-1` · Araç: [[Sipariş Stok]]

## Ne yapar
- Çimento stoğunu söyle
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
