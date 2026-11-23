---
tip: fonksiyon
kod: "09.02.02-2"
arac: "[[Kira Tahsilat]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Gecikme tutarını hesapla

> Kod `09.02.02-2` · Araç: [[Kira Tahsilat]]

## Ne yapar
- Gecikme tutarını hesapla
- Bağlı modül: Muhasebe & Gelir-Gider genişlemesi: kira vade, gecikme ve dekont eşlemesi.

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
