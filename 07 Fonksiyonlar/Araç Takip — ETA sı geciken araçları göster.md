---
tip: fonksiyon
kod: "12.00.07-2"
arac: "[[Araç Takip]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# ETA sı geciken araçları göster

> Kod `12.00.07-2` · Araç: [[Araç Takip]]

## Ne yapar
- ETA sı geciken araçları göster
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
