---
tip: fonksiyon
kod: "10.07.02-1"
arac: "[[Denetim Tutanak]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bugünkü denetim tutanağını yaz

> Kod `10.07.02-1` · Araç: [[Denetim Tutanak]]

## Ne yapar
- Bugünkü denetim tutanağını yaz
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
