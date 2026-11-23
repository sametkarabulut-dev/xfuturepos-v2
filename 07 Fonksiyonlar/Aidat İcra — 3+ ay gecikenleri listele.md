---
tip: fonksiyon
kod: "09.03.05-1"
arac: "[[Aidat İcra]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# 3+ ay gecikenleri listele

> Kod `09.03.05-1` · Araç: [[Aidat İcra]]

## Ne yapar
- 3+ ay gecikenleri listele
- Bağlı modül: Gecikme tazminatı hesabı ve icra dosya hazırlığı; takip başlatma insan onaylı.

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
