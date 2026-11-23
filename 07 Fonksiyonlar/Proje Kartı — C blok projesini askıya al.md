---
tip: fonksiyon
kod: "10.00.01-2"
arac: "[[Proje Kartı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# C blok projesini askıya al

> Kod `10.00.01-2` · Araç: [[Proje Kartı]]

## Ne yapar
- C blok projesini askıya al
- Bağlı modül: Şantiye/iş kartı; CRM genişlemesi.

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
