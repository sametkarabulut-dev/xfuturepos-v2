---
tip: fonksiyon
kod: "16.02.03-1"
arac: "[[Gün checklist]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Nikah günü checklist

> Kod `16.02.03-1` · Araç: [[Gün checklist]]

## Ne yapar
- Nikah günü checklist
- Bağlı modül: Planlayıcı saha kontrol listesi.

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
