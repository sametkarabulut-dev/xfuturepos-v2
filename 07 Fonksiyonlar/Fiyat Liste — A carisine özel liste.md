---
tip: fonksiyon
kod: "10.05.04-2"
arac: "[[Fiyat Liste]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# A carisine özel liste

> Kod `10.05.04-2` · Araç: [[Fiyat Liste]]

## Ne yapar
- A carisine özel liste
- Bağlı modül: Cari/şantiye fiyat.

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
