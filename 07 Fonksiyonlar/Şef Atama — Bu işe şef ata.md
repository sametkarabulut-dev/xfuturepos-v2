---
tip: fonksiyon
kod: "10.01.04-1"
arac: "[[Şef Atama]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu işe şef ata

> Kod `10.01.04-1` · Araç: [[Şef Atama]]

## Ne yapar
- Bu işe şef ata
- Bağlı modül: Şantiye şefi atama ve limit.

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
