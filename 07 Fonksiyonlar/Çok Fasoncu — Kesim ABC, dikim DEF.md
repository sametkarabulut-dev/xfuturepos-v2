---
tip: fonksiyon
kod: "13.06.05-1"
arac: "[[Çok Fasoncu]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kesim ABC, dikim DEF

> Kod `13.06.05-1` · Araç: [[Çok Fasoncu]]

## Ne yapar
- Kesim ABC, dikim DEF
- Bağlı modül: Operasyon bazlı farklı fasoncular

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
