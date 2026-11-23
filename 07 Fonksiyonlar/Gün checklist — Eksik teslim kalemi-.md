---
tip: fonksiyon
kod: "16.02.03-2"
arac: "[[Gün checklist]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Eksik teslim kalemi?

> Kod `16.02.03-2` · Araç: [[Gün checklist]]

## Ne yapar
- Eksik teslim kalemi?
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
