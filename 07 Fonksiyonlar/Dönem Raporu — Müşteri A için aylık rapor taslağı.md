---
tip: fonksiyon
kod: "15.02.03-1"
arac: "[[Dönem Raporu]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Müşteri A için aylık rapor taslağı

> Kod `15.02.03-1` · Araç: [[Dönem Raporu]]

## Ne yapar
- Müşteri A için aylık rapor taslağı
- Bağlı modül: Dönem harcama, tıklama ve dönüşüm özeti.

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
