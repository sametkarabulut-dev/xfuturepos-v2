---
tip: fonksiyon
kod: "10.07.01-2"
arac: "[[YİBF Takip]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Şefi istifa eden işler

> Kod `10.07.01-2` · Araç: [[YİBF Takip]]

## Ne yapar
- Şefi istifa eden işler
- Bağlı modül: YİBF ve atama takibi.

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
