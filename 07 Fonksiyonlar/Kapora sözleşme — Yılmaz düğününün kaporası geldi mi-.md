---
tip: fonksiyon
kod: "16.00.02-1"
arac: "[[Kapora sözleşme]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yılmaz düğününün kaporası geldi mi?

> Kod `16.00.02-1` · Araç: [[Kapora sözleşme]]

## Ne yapar
- Yılmaz düğününün kaporası geldi mi?
- Bağlı modül: Opsiyon, kapora, kesinleşme, kalan bakiye ve iade kuralı.

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
