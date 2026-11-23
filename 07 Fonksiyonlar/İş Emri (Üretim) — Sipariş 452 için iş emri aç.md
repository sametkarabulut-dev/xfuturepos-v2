---
tip: fonksiyon
kod: "13.00.01-1"
arac: "[[İş Emri (Üretim)]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Sipariş 452 için iş emri aç

> Kod `13.00.01-1` · Araç: [[İş Emri (Üretim)]]

## Ne yapar
- Sipariş 452 için iş emri aç
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
