---
tip: fonksiyon
kod: "10.06.05-2"
arac: "[[Ruhsat Evrak]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Eksik paftalar

> Kod `10.06.05-2` · Araç: [[Ruhsat Evrak]]

## Ne yapar
- Eksik paftalar
- Bağlı modül: İdare evrak paketi.

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
