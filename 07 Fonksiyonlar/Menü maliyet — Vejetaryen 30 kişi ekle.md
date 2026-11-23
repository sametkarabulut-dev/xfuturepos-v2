---
tip: fonksiyon
kod: "16.06.01-2"
arac: "[[Menü maliyet]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Vejetaryen 30 kişi ekle

> Kod `16.06.01-2` · Araç: [[Menü maliyet]]

## Ne yapar
- Vejetaryen 30 kişi ekle
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
