---
tip: fonksiyon
kod: "15.07.02-2"
arac: "[[Kurulum Kaydı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Eğitimi tamamlanmayanları listele

> Kod `15.07.02-2` · Araç: [[Kurulum Kaydı]]

## Ne yapar
- Eğitimi tamamlanmayanları listele
- Bağlı modül: Kurulum, eğitim ve müşteri ortam kaydı.

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
