---
tip: fonksiyon
kod: "16.04.01-1"
arac: "[[Gösteri dosya]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Cuma teknik rider eksikleri?

> Kod `16.04.01-1` · Araç: [[Gösteri dosya]]

## Ne yapar
- Cuma teknik rider eksikleri?
- Bağlı modül: Sanatçı, rider, mekân/alan ve çağrı saatleri.

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
