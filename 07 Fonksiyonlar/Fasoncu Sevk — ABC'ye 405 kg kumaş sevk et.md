---
tip: fonksiyon
kod: "13.06.01-1"
arac: "[[Fasoncu Sevk]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# ABC'ye 405 kg kumaş sevk et

> Kod `13.06.01-1` · Araç: [[Fasoncu Sevk]]

## Ne yapar
- ABC'ye 405 kg kumaş sevk et
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
