---
tip: fonksiyon
kod: "12.06.02-2"
arac: "[[Booking Emri]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Açık bookingleri listele

> Kod `12.06.02-2` · Araç: [[Booking Emri]]

## Ne yapar
- Açık bookingleri listele
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
