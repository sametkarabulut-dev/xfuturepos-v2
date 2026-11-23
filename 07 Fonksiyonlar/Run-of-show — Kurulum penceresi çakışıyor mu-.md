---
tip: fonksiyon
kod: "16.00.04-1"
arac: "[[Run-of-show]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kurulum penceresi çakışıyor mu?

> Kod `16.00.04-1` · Araç: [[Run-of-show]]

## Ne yapar
- Kurulum penceresi çakışıyor mu?
- Bağlı modül: Etkinlik günü zaman akışı ve bağımlı kalemler.

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
