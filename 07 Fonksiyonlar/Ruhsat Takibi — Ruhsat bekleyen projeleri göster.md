---
tip: fonksiyon
kod: "10.01.01-1"
arac: "[[Ruhsat Takibi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Ruhsat bekleyen projeleri göster

> Kod `10.01.01-1` · Araç: [[Ruhsat Takibi]]

## Ne yapar
- Ruhsat bekleyen projeleri göster
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
