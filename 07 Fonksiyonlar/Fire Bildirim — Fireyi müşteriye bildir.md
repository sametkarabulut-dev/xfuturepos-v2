---
tip: fonksiyon
kod: "13.03.04-1"
arac: "[[Fire Bildirim]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Fireyi müşteriye bildir

> Kod `13.03.04-1` · Araç: [[Fire Bildirim]]

## Ne yapar
- Fireyi müşteriye bildir
- Bağlı modül: Müşteri malzemesinde fire raporu

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
