---
tip: fonksiyon
kod: "15.00.01-1"
arac: "[[Proje Kapsamı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu yazışmayı kapsam maddesine çevir

> Kod `15.00.01-1` · Araç: [[Proje Kapsamı]]

## Ne yapar
- Bu yazışmayı kapsam maddesine çevir
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
