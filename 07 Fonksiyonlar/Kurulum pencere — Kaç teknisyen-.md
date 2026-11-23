---
tip: fonksiyon
kod: "16.05.02-2"
arac: "[[Kurulum pencere]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kaç teknisyen?

> Kod `16.05.02-2` · Araç: [[Kurulum pencere]]

## Ne yapar
- Kaç teknisyen?
- Bağlı modül: Load-in/out pencereleri ve ekip çağrısı.

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
