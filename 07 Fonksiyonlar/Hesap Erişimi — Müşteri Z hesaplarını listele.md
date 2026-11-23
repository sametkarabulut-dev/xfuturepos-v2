---
tip: fonksiyon
kod: "15.02.01-2"
arac: "[[Hesap Erişimi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Müşteri Z hesaplarını listele

> Kod `15.02.01-2` · Araç: [[Hesap Erişimi]]

## Ne yapar
- Müşteri Z hesaplarını listele
- Bağlı modül: Müşteri reklam hesabı ve MCC/BM erişim durumu.

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
