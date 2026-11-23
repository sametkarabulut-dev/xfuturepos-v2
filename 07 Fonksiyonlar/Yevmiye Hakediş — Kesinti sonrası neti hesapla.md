---
tip: fonksiyon
kod: "10.02.02-2"
arac: "[[Yevmiye Hakediş]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kesinti sonrası neti hesapla

> Kod `10.02.02-2` · Araç: [[Yevmiye Hakediş]]

## Ne yapar
- Kesinti sonrası neti hesapla
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
