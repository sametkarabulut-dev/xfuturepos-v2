---
tip: fonksiyon
kod: "15.01.04-1"
arac: "[[Ortam Envanteri]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Müşteri ortam kartını özetle

> Kod `15.01.04-1` · Araç: [[Ortam Envanteri]]

## Ne yapar
- Müşteri ortam kartını özetle
- Bağlı modül: Müşteri ortamı, erişim ve sürüm kaydı.

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
