---
tip: fonksiyon
kod: "10.02.02-1"
arac: "[[Yevmiye Hakediş]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu ay hakedişimi hazırla

> Kod `10.02.02-1` · Araç: [[Yevmiye Hakediş]]

## Ne yapar
- Bu ay hakedişimi hazırla
- Bağlı modül: Taşeron hakediş paketi.

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
