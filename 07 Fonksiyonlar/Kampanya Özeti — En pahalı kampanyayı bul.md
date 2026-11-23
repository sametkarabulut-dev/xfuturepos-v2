---
tip: fonksiyon
kod: "15.02.04-2"
arac: "[[Kampanya Özeti]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# En pahalı kampanyayı bul

> Kod `15.02.04-2` · Araç: [[Kampanya Özeti]]

## Ne yapar
- En pahalı kampanyayı bul
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
