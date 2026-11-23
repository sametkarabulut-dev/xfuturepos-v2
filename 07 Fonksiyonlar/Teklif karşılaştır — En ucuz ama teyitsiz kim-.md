---
tip: fonksiyon
kod: "16.02.02-2"
arac: "[[Teklif karşılaştır]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# En ucuz ama teyitsiz kim?

> Kod `16.02.02-2` · Araç: [[Teklif karşılaştır]]

## Ne yapar
- En ucuz ama teyitsiz kim?
- Bağlı modül: Aynı hizmet kalemine gelen teklif ve teyit durumu.

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
