---
tip: fonksiyon
kod: "12.00.07-1"
arac: "[[Araç Takip]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# 34 ABC 123 son bilinen konum

> Kod `12.00.07-1` · Araç: [[Araç Takip]]

## Ne yapar
- 34 ABC 123 son bilinen konum
- Bağlı modül: Harici filo takip konumunu sevkiyata bağlar; marka API iddiası doğrulanmadan bağlanır.

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
