---
tip: fonksiyon
kod: "12.06.03-1"
arac: "[[TİO Belge]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# TİO belgesi bitiş tarihi

> Kod `12.06.03-1` · Araç: [[TİO Belge]]

## Ne yapar
- TİO belgesi bitiş tarihi
- Bağlı modül: TİO belgesi (eski R1/R2) ve G1 acente ayrımı.

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
