---
tip: fonksiyon
kod: "12.04.01-1"
arac: "[[Durak Rotası]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bugünkü 18 durağı sırala

> Kod `12.04.01-1` · Araç: [[Durak Rotası]]

## Ne yapar
- Bugünkü 18 durağı sırala
- Bağlı modül: Çok duraklı teslim sırası; kurye gönderisi boyutu notu.

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
