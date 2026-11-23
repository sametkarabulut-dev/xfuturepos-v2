---
tip: fonksiyon
kod: "16.05.03-1"
arac: "[[Dönüş sayım]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Dönüşte eksik ne?

> Kod `16.05.03-1` · Araç: [[Dönüş sayım]]

## Ne yapar
- Dönüşte eksik ne?
- Bağlı modül: Çıkış fişi ile dönüş sayımı; eksik/hasar.

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
