---
tip: fonksiyon
kod: "15.05.04-2"
arac: "[[Plan Karşılaştırma]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bütçe aşımını özetle

> Kod `15.05.04-2` · Araç: [[Plan Karşılaştırma]]

## Ne yapar
- Bütçe aşımını özetle
- Bağlı modül: Plan ile gerçekleşen maliyet/yerleşim sapması.

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
