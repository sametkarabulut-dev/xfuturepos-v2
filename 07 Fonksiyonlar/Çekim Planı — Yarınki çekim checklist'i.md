---
tip: fonksiyon
kod: "15.04.04-1"
arac: "[[Çekim Planı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yarınki çekim checklist'i

> Kod `15.04.04-1` · Araç: [[Çekim Planı]]

## Ne yapar
- Yarınki çekim checklist'i
- Bağlı modül: Çekim günü, ekip ve lokasyon checklist'i.

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
