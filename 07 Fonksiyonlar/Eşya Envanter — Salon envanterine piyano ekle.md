---
tip: fonksiyon
kod: "12.05.02-1"
arac: "[[Eşya Envanter]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Salon envanterine piyano ekle

> Kod `12.05.02-1` · Araç: [[Eşya Envanter]]

## Ne yapar
- Salon envanterine piyano ekle
- Bağlı modül: Oda bazlı eşya listesi, kırılgan ve demontaj notları.

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
