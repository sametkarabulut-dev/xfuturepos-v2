---
tip: fonksiyon
kod: "12.06.02-1"
arac: "[[Booking Emri]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Booking 220 yi Ahmet Lojistik e ver

> Kod `12.06.02-1` · Araç: [[Booking Emri]]

## Ne yapar
- Booking 220 yi Ahmet Lojistik e ver
- Bağlı modül: Müşteri emrini taşıyıcı iş emrine çevirir; alış/satış navlun marjı tutar.

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
