---
tip: fonksiyon
kod: "09.02.02-1"
arac: "[[Kira Tahsilat]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu ay ödenmeyen kiraları getir

> Kod `09.02.02-1` · Araç: [[Kira Tahsilat]]

## Ne yapar
- Bu ay ödenmeyen kiraları getir
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
