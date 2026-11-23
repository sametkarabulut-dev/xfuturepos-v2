---
tip: fonksiyon
kod: "09.00.06-1"
arac: "[[Belge Kasası]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu portföyün tapu belgelerini listele

> Kod `09.00.06-1` · Araç: [[Belge Kasası]]

## Ne yapar
- Bu portföyün tapu belgelerini listele
- Bağlı modül: Tapu, kimlik, yetki ve ekspertiz belgelerinin versiyonlu arşivi.

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
