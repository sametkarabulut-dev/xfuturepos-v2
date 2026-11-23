---
tip: fonksiyon
kod: "10.04.02-1"
arac: "[[Teklif Onay]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Banyo tadilat teklifi gönder

> Kod `10.04.02-1` · Araç: [[Teklif Onay]]

## Ne yapar
- Banyo tadilat teklifi gönder
- Bağlı modül: Teklif, kapora, onay.

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
