---
tip: fonksiyon
kod: "15.01.01-2"
arac: "[[Sprint Tahtası]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Sprint bitiş özeti yaz

> Kod `15.01.01-2` · Araç: [[Sprint Tahtası]]

## Ne yapar
- Sprint bitiş özeti yaz
- Bağlı modül: Sprint işleri, durum ve engeller.

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
