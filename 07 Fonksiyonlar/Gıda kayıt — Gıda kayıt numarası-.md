---
tip: fonksiyon
kod: "16.06.03-1"
arac: "[[Gıda kayıt]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Gıda kayıt numarası?

> Kod `16.06.03-1` · Araç: [[Gıda kayıt]]

## Ne yapar
- Gıda kayıt numarası?
- Bağlı modül: İşletme kayıt belgesi ve faaliyet konusu dosyası.

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
