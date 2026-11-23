---
tip: fonksiyon
kod: "15.03.04-1"
arac: "[[SEO İşleri]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu ayın SEO işlerini özetle

> Kod `15.03.04-1` · Araç: [[SEO İşleri]]

## Ne yapar
- Bu ayın SEO işlerini özetle
- Bağlı modül: SEO iş listesi ve sayfa/anahtar kelime takibi.

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
