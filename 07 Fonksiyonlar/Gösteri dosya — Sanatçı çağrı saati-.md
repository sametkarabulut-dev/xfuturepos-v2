---
tip: fonksiyon
kod: "16.04.01-2"
arac: "[[Gösteri dosya]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Sanatçı çağrı saati?

> Kod `16.04.01-2` · Araç: [[Gösteri dosya]]

## Ne yapar
- Sanatçı çağrı saati?
- Bağlı modül: Sanatçı, rider, mekân/alan ve çağrı saatleri.

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
