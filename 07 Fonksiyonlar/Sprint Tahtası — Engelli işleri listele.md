---
tip: fonksiyon
kod: "15.01.01-1"
arac: "[[Sprint Tahtası]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Engelli işleri listele

> Kod `15.01.01-1` · Araç: [[Sprint Tahtası]]

## Ne yapar
- Engelli işleri listele
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
