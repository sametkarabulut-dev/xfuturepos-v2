---
tip: fonksiyon
kod: "12.02.05-1"
arac: "[[Geçiş İzni]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Romanya geçiş izni kalan adet

> Kod `12.02.05-1` · Araç: [[Geçiş İzni]]

## Ne yapar
- Romanya geçiş izni kalan adet
- Bağlı modül: Ülke geçiş belgesi stok ve kullanım kaydı.

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
