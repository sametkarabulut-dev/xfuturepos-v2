---
tip: fonksiyon
kod: "13.02.05-1"
arac: "[[Alternatif Reçete]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Alternatif reçeteyi uygula

> Kod `13.02.05-1` · Araç: [[Alternatif Reçete]]

## Ne yapar
- Alternatif reçeteyi uygula
- Bağlı modül: Malzeme yokluğunda alternatif BOM

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
