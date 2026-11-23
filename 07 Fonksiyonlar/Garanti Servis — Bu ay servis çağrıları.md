---
tip: fonksiyon
kod: "10.04.05-2"
arac: "[[Garanti Servis]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu ay servis çağrıları

> Kod `10.04.05-2` · Araç: [[Garanti Servis]]

## Ne yapar
- Bu ay servis çağrıları
- Bağlı modül: Teslim sonrası servis.

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
