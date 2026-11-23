---
tip: fonksiyon
kod: "09.01.05-1"
arac: "[[Piyasa Bandı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu daire için fiyat bandı öner

> Kod `09.01.05-1` · Araç: [[Piyasa Bandı]]

## Ne yapar
- Bu daire için fiyat bandı öner
- Bağlı modül: Benzer ilanlardan bilgilendirme amaçlı fiyat bandı önerisi.

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
