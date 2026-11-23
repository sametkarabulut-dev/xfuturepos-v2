---
tip: fonksiyon
kod: "15.02.04-1"
arac: "[[Kampanya Özeti]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Duraklayan kampanyaları listele

> Kod `15.02.04-1` · Araç: [[Kampanya Özeti]]

## Ne yapar
- Duraklayan kampanyaları listele
- Bağlı modül: Kampanya ve ad set durum özeti.

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
