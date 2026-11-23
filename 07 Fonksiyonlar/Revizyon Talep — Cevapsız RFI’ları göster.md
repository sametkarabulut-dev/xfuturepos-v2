---
tip: fonksiyon
kod: "10.03.05-2"
arac: "[[Revizyon Talep]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Cevapsız RFI’ları göster

> Kod `10.03.05-2` · Araç: [[Revizyon Talep]]

## Ne yapar
- Cevapsız RFI’ları göster
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
