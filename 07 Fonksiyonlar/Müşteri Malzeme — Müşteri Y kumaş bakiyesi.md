---
tip: fonksiyon
kod: "13.03.01-1"
arac: "[[Müşteri Malzeme]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Müşteri Y kumaş bakiyesi

> Kod `13.03.01-1` · Araç: [[Müşteri Malzeme]]

## Ne yapar
- Müşteri Y kumaş bakiyesi
- Bağlı modül: Müşteri emanet hammadde bakiyesi

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
