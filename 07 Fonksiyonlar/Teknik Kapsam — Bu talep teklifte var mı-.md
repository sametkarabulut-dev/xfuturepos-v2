---
tip: fonksiyon
kod: "15.01.03-1"
arac: "[[Teknik Kapsam]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu talep teklifte var mı?

> Kod `15.01.03-1` · Araç: [[Teknik Kapsam]]

## Ne yapar
- Bu talep teklifte var mı?
- Bağlı modül: Teknik madde takibi ve kapsam dışı geliştirme işareti.

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
