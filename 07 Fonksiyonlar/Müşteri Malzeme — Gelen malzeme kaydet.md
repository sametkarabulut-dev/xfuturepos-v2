---
tip: fonksiyon
kod: "13.03.01-2"
arac: "[[Müşteri Malzeme]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Gelen malzeme kaydet

> Kod `13.03.01-2` · Araç: [[Müşteri Malzeme]]

## Ne yapar
- Gelen malzeme kaydet
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
