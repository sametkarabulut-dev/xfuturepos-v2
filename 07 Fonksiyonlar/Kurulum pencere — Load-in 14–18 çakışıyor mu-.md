---
tip: fonksiyon
kod: "16.05.02-1"
arac: "[[Kurulum pencere]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Load-in 14–18 çakışıyor mu?

> Kod `16.05.02-1` · Araç: [[Kurulum pencere]]

## Ne yapar
- Load-in 14–18 çakışıyor mu?
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
