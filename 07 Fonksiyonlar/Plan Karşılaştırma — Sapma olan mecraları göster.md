---
tip: fonksiyon
kod: "15.05.04-1"
arac: "[[Plan Karşılaştırma]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Sapma olan mecraları göster

> Kod `15.05.04-1` · Araç: [[Plan Karşılaştırma]]

## Ne yapar
- Sapma olan mecraları göster
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
