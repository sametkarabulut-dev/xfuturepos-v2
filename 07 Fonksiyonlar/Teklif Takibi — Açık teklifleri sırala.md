---
tip: fonksiyon
kod: "09.01.03-1"
arac: "[[Teklif Takibi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Açık teklifleri sırala

> Kod `09.01.03-1` · Araç: [[Teklif Takibi]]

## Ne yapar
- Açık teklifleri sırala
- Bağlı modül: Alıcı teklifleri, karşı teklif ve durum pipeline'ı.

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
