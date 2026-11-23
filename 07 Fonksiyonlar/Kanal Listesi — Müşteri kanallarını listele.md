---
tip: fonksiyon
kod: "15.03.03-1"
arac: "[[Kanal Listesi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Müşteri kanallarını listele

> Kod `15.03.03-1` · Araç: [[Kanal Listesi]]

## Ne yapar
- Müşteri kanallarını listele
- Bağlı modül: Müşteri kanal ve hesap envanteri.

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
