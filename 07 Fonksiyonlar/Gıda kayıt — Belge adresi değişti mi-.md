---
tip: fonksiyon
kod: "16.06.03-2"
arac: "[[Gıda kayıt]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Belge adresi değişti mi?

> Kod `16.06.03-2` · Araç: [[Gıda kayıt]]

## Ne yapar
- Belge adresi değişti mi?
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
