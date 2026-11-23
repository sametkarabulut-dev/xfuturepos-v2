---
tip: fonksiyon
kod: "16.06.01-1"
arac: "[[Menü maliyet]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# 220 kişilik menü maliyeti?

> Kod `16.06.01-1` · Araç: [[Menü maliyet]]

## Ne yapar
- 220 kişilik menü maliyeti?
- Bağlı modül: Reçete, kişi başı maliyet ve teklif.

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
