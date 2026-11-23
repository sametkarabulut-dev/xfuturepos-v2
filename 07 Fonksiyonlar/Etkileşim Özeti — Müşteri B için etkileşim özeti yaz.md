---
tip: fonksiyon
kod: "15.03.05-1"
arac: "[[Etkileşim Özeti]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Müşteri B için etkileşim özeti yaz

> Kod `15.03.05-1` · Araç: [[Etkileşim Özeti]]

## Ne yapar
- Müşteri B için etkileşim özeti yaz
- Bağlı modül: Dönem etkileşim ve müşteri rapor taslağı.

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
