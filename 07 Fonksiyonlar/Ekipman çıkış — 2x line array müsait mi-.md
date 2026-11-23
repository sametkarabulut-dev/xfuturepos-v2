---
tip: fonksiyon
kod: "16.05.01-1"
arac: "[[Ekipman çıkış]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# 2x line array müsait mi?

> Kod `16.05.01-1` · Araç: [[Ekipman çıkış]]

## Ne yapar
- 2x line array müsait mi?
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
