---
tip: fonksiyon
kod: "13.04.02-2"
arac: "[[Montaj Aşama]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Test aşamasına geç

> Kod `13.04.02-2` · Araç: [[Montaj Aşama]]

## Ne yapar
- Test aşamasına geç
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
