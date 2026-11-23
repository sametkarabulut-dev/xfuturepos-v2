---
tip: fonksiyon
kod: "16.03.02-1"
arac: "[[Kurulum oturum]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# İkinci gün 14:00 oturumu?

> Kod `16.03.02-1` · Araç: [[Kurulum oturum]]

## Ne yapar
- İkinci gün 14:00 oturumu?
- Bağlı modül: Load-in ve oturum/speaker zaman blokları.

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
