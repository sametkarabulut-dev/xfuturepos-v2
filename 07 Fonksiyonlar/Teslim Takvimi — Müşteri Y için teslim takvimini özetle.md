---
tip: fonksiyon
kod: "15.00.04-2"
arac: "[[Teslim Takvimi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Müşteri Y için teslim takvimini özetle

> Kod `15.00.04-2` · Araç: [[Teslim Takvimi]]

## Ne yapar
- Müşteri Y için teslim takvimini özetle
- Bağlı modül: Teslim tarihleri, bağımlılıklar ve gecikme riski.

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
