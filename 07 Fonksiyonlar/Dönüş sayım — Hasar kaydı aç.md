---
tip: fonksiyon
kod: "16.05.03-2"
arac: "[[Dönüş sayım]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Hasar kaydı aç

> Kod `16.05.03-2` · Araç: [[Dönüş sayım]]

## Ne yapar
- Hasar kaydı aç
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
