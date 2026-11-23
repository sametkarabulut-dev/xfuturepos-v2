---
tip: fonksiyon
kod: "10.07.02-2"
arac: "[[Denetim Tutanak]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Açık uygunsuzluklar

> Kod `10.07.02-2` · Araç: [[Denetim Tutanak]]

## Ne yapar
- Açık uygunsuzluklar
- Bağlı modül: Saha denetim ve uygunsuzluk.

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
