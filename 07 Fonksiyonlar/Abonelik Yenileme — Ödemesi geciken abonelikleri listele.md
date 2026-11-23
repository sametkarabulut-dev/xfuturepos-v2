---
tip: fonksiyon
kod: "15.08.01-2"
arac: "[[Abonelik Yenileme]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Ödemesi geciken abonelikleri listele

> Kod `15.08.01-2` · Araç: [[Abonelik Yenileme]]

## Ne yapar
- Ödemesi geciken abonelikleri listele
- Bağlı modül: Abonelik dönemi, yenileme ve churn riski.

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
