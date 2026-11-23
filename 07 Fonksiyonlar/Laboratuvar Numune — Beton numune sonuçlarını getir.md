---
tip: fonksiyon
kod: "10.07.04-1"
arac: "[[Laboratuvar Numune]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Beton numune sonuçlarını getir

> Kod `10.07.04-1` · Araç: [[Laboratuvar Numune]]

## Ne yapar
- Beton numune sonuçlarını getir
- Bağlı modül: Numune ve sonuç.

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
