---
tip: fonksiyon
kod: "10.04.01-2"
arac: "[[Keşif Randevu]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu hafta keşifleri listele

> Kod `10.04.01-2` · Araç: [[Keşif Randevu]]

## Ne yapar
- Bu hafta keşifleri listele
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
