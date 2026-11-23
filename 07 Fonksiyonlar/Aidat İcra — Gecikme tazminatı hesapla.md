---
tip: fonksiyon
kod: "09.03.05-2"
arac: "[[Aidat İcra]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Gecikme tazminatı hesapla

> Kod `09.03.05-2` · Araç: [[Aidat İcra]]

## Ne yapar
- Gecikme tazminatı hesapla
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
