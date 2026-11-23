---
tip: fonksiyon
kod: "15.08.01-1"
arac: "[[Abonelik Yenileme]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# 14 gün içinde yenilenecekleri göster

> Kod `15.08.01-1` · Araç: [[Abonelik Yenileme]]

## Ne yapar
- 14 gün içinde yenilenecekleri göster
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
