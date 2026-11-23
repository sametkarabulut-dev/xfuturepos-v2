---
tip: fonksiyon
kod: "15.03.03-2"
arac: "[[Kanal Listesi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Erişimi belirsiz kanalları bul

> Kod `15.03.03-2` · Araç: [[Kanal Listesi]]

## Ne yapar
- Erişimi belirsiz kanalları bul
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
