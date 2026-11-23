---
tip: fonksiyon
kod: "15.00.01-2"
arac: "[[Proje Kapsamı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kapsam dışı satırları listele

> Kod `15.00.01-2` · Araç: [[Proje Kapsamı]]

## Ne yapar
- Kapsam dışı satırları listele
- Bağlı modül: Sözleşme ve teklif maddeleri, kabul kriteri, kapsam dışı iş talebi kaydı; kapsam sapmasını görünür kılar.

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
