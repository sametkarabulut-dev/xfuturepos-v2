---
tip: fonksiyon
kod: "13.00.01-2"
arac: "[[İş Emri (Üretim)]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Geciken iş emirlerini listele

> Kod `13.00.01-2` · Araç: [[İş Emri (Üretim)]]

## Ne yapar
- Geciken iş emirlerini listele
- Bağlı modül: Sipariş veya stok ihtiyacından iş emri; durum akışı; tam MES değil

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
