---
tip: fonksiyon
kod: "15.00.03-1"
arac: "[[Brief Onayı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Brief'ten iş listesi çıkar

> Kod `15.00.03-1` · Araç: [[Brief Onayı]]

## Ne yapar
- Brief'ten iş listesi çıkar
- Bağlı modül: Brief, sürüm ve revizyon turu; müşteri onayı kuyruğu.

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
