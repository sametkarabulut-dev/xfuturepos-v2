---
tip: fonksiyon
kod: "13.04.05-1"
arac: "[[Saha Sevk]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Sevkiyat checklist

> Kod `13.04.05-1` · Araç: [[Saha Sevk]]

## Ne yapar
- Sevkiyat checklist
- Bağlı modül: Makine sevkiyat checklist

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
