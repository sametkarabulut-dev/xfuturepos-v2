---
tip: fonksiyon
kod: "15.04.04-2"
arac: "[[Çekim Planı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Eksik ekipmanı listele

> Kod `15.04.04-2` · Araç: [[Çekim Planı]]

## Ne yapar
- Eksik ekipmanı listele
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
