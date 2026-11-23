---
tip: fonksiyon
kod: "10.05.02-2"
arac: "[[Sevkiyat İrsaliye]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# e-İrsaliye kes

> Kod `10.05.02-2` · Araç: [[Sevkiyat İrsaliye]]

## Ne yapar
- e-İrsaliye kes
- Bağlı modül: Sevk + e-İrsaliye. Çekirdek genişleme: e-Fatura.

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
