---
tip: fonksiyon
kod: "13.04.02-1"
arac: "[[Montaj Aşama]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# P-12 hangi aşamada

> Kod `13.04.02-1` · Araç: [[Montaj Aşama]]

## Ne yapar
- P-12 hangi aşamada
- Bağlı modül: Kesim-kaynak-montaj-test kapıları

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
