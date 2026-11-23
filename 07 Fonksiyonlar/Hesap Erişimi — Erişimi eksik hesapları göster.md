---
tip: fonksiyon
kod: "15.02.01-1"
arac: "[[Hesap Erişimi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Erişimi eksik hesapları göster

> Kod `15.02.01-1` · Araç: [[Hesap Erişimi]]

## Ne yapar
- Erişimi eksik hesapları göster
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
