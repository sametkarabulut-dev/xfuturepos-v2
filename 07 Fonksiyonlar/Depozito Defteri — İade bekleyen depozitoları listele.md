---
tip: fonksiyon
kod: "09.02.05-1"
arac: "[[Depozito Defteri]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# İade bekleyen depozitoları listele

> Kod `09.02.05-1` · Araç: [[Depozito Defteri]]

## Ne yapar
- İade bekleyen depozitoları listele
- Bağlı modül: Depozito alma, iade, mahsup ve belgelendirme.

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
