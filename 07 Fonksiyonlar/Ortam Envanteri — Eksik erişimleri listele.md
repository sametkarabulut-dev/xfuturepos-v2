---
tip: fonksiyon
kod: "15.01.04-2"
arac: "[[Ortam Envanteri]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Eksik erişimleri listele

> Kod `15.01.04-2` · Araç: [[Ortam Envanteri]]

## Ne yapar
- Eksik erişimleri listele
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
