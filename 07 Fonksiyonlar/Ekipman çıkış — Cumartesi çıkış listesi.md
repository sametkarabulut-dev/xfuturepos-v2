---
tip: fonksiyon
kod: "16.05.01-2"
arac: "[[Ekipman çıkış]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Cumartesi çıkış listesi

> Kod `16.05.01-2` · Araç: [[Ekipman çıkış]]

## Ne yapar
- Cumartesi çıkış listesi
- Bağlı modül: Ekipman parkı, işe çıkış fişi ve rezervasyon kilidi.

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
