---
tip: fonksiyon
kod: "12.06.04-1"
arac: "[[Multimodal Plan]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Mersin liman bacağını plana ekle

> Kod `12.06.04-1` · Araç: [[Multimodal Plan]]

## Ne yapar
- Mersin liman bacağını plana ekle
- Bağlı modül: Kara + deniz/hava bacak checklisti.

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
