---
tip: fonksiyon
kod: "16.02.02-1"
arac: "[[Teklif karşılaştır]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Üç fotoğraf teklifini karşılaştır

> Kod `16.02.02-1` · Araç: [[Teklif karşılaştır]]

## Ne yapar
- Üç fotoğraf teklifini karşılaştır
- Bağlı modül: Aynı hizmet kalemine gelen teklif ve teyit durumu.

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
