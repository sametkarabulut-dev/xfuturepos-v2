---
tip: fonksiyon
kod: "15.03.04-2"
arac: "[[SEO İşleri]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yarım kalan sayfa işlerini listele

> Kod `15.03.04-2` · Araç: [[SEO İşleri]]

## Ne yapar
- Yarım kalan sayfa işlerini listele
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
