---
tip: fonksiyon
kod: "13.02.01-2"
arac: "[[Parti Plan]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu ay planı

> Kod `13.02.01-2` · Araç: [[Parti Plan]]

## Ne yapar
- Bu ay planı
- Bağlı modül: Stok/talep ile parti ve iş emri

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
