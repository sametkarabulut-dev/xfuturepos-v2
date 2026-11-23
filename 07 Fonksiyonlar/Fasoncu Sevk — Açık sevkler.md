---
tip: fonksiyon
kod: "13.06.01-2"
arac: "[[Fasoncu Sevk]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Açık sevkler

> Kod `13.06.01-2` · Araç: [[Fasoncu Sevk]]

## Ne yapar
- Açık sevkler
- Bağlı modül: Fasoncuya malzeme sevk ve iş emri bağlama

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
