---
tip: fonksiyon
kod: "10.07.04-2"
arac: "[[Laboratuvar Numune]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Ret edilen numuneler

> Kod `10.07.04-2` · Araç: [[Laboratuvar Numune]]

## Ne yapar
- Ret edilen numuneler
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
