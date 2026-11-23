---
tip: fonksiyon
kod: "13.04.01-2"
arac: "[[Proje BOM]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Revizyon farkını göster

> Kod `13.04.01-2` · Araç: [[Proje BOM]]

## Ne yapar
- Revizyon farkını göster
- Bağlı modül: Projeye özel reçete revizyonları

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
