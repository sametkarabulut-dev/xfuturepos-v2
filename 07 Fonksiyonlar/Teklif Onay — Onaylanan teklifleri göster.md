---
tip: fonksiyon
kod: "10.04.02-2"
arac: "[[Teklif Onay]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Onaylanan teklifleri göster

> Kod `10.04.02-2` · Araç: [[Teklif Onay]]

## Ne yapar
- Onaylanan teklifleri göster
- Bağlı modül: Teklif, kapora, onay.

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
