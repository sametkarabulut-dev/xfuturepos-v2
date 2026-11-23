---
tip: fonksiyon
kod: "09.00.06-2"
arac: "[[Belge Kasası]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Süresi dolan belgeleri bul

> Kod `09.00.06-2` · Araç: [[Belge Kasası]]

## Ne yapar
- Süresi dolan belgeleri bul
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
