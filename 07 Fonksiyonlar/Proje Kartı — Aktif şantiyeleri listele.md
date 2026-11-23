---
tip: fonksiyon
kod: "10.00.01-1"
arac: "[[Proje Kartı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Aktif şantiyeleri listele

> Kod `10.00.01-1` · Araç: [[Proje Kartı]]

## Ne yapar
- Aktif şantiyeleri listele
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
