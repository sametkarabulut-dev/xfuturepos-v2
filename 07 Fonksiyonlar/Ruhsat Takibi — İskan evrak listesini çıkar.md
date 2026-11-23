---
tip: fonksiyon
kod: "10.01.01-2"
arac: "[[Ruhsat Takibi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# İskan evrak listesini çıkar

> Kod `10.01.01-2` · Araç: [[Ruhsat Takibi]]

## Ne yapar
- İskan evrak listesini çıkar
- Bağlı modül: Ruhsat-iskan evrak ve adım takibi.

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
