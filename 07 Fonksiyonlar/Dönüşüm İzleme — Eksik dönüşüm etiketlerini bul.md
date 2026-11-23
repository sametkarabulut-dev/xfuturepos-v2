---
tip: fonksiyon
kod: "15.02.05-1"
arac: "[[Dönüşüm İzleme]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Eksik dönüşüm etiketlerini bul

> Kod `15.02.05-1` · Araç: [[Dönüşüm İzleme]]

## Ne yapar
- Eksik dönüşüm etiketlerini bul
- Bağlı modül: Dönüşüm ve etiket eşleme kontrolü.

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
