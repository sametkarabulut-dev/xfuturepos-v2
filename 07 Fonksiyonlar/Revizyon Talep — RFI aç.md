---
tip: fonksiyon
kod: "10.03.05-1"
arac: "[[Revizyon Talep]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# RFI aç

> Kod `10.03.05-1` · Araç: [[Revizyon Talep]]

## Ne yapar
- RFI aç
- Bağlı modül: Sahadan RFI.

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
