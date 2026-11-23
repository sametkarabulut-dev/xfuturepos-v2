---
tip: fonksiyon
kod: "15.01.03-2"
arac: "[[Teknik Kapsam]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kapsam dışı PR'ları işaretle

> Kod `15.01.03-2` · Araç: [[Teknik Kapsam]]

## Ne yapar
- Kapsam dışı PR'ları işaretle
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
