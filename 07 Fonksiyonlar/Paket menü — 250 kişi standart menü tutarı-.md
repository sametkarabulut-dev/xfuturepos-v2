---
tip: fonksiyon
kod: "16.01.02-1"
arac: "[[Paket menü]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# 250 kişi standart menü tutarı?

> Kod `16.01.02-1` · Araç: [[Paket menü]]

## Ne yapar
- 250 kişi standart menü tutarı?
- Bağlı modül: Kişi başı paket, ek hizmet ve toplam tutar.

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
