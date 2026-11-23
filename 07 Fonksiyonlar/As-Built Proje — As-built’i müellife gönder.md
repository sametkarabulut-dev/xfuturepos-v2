---
tip: fonksiyon
kod: "10.03.04-1"
arac: "[[As-Built Proje]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# As-built’i müellife gönder

> Kod `10.03.04-1` · Araç: [[As-Built Proje]]

## Ne yapar
- As-built’i müellife gönder
- Bağlı modül: Uygulama sonrası çizim teslimi.

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
