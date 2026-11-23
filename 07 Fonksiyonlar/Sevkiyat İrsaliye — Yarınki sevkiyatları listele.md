---
tip: fonksiyon
kod: "10.05.02-1"
arac: "[[Sevkiyat İrsaliye]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yarınki sevkiyatları listele

> Kod `10.05.02-1` · Araç: [[Sevkiyat İrsaliye]]

## Ne yapar
- Yarınki sevkiyatları listele
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
