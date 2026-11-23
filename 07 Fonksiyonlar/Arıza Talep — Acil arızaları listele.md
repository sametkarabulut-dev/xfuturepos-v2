---
tip: fonksiyon
kod: "09.03.03-1"
arac: "[[Arıza Talep]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Acil arızaları listele

> Kod `09.03.03-1` · Araç: [[Arıza Talep]]

## Ne yapar
- Acil arızaları listele
- Bağlı modül: Kat maliki/kiracı talep, teknisyen atama ve SLA.

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
