---
tip: fonksiyon
kod: "13.02.01-1"
arac: "[[Parti Plan]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# SKU-A için 500'lük parti aç

> Kod `13.02.01-1` · Araç: [[Parti Plan]]

## Ne yapar
- SKU-A için 500'lük parti aç
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
