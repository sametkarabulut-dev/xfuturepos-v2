---
tip: fonksiyon
kod: "10.04.01-1"
arac: "[[Keşif Randevu]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yarın keşif randevusu koy

> Kod `10.04.01-1` · Araç: [[Keşif Randevu]]

## Ne yapar
- Yarın keşif randevusu koy
- Bağlı modül: Keşif randevusu; CRM genişlemesi.

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
