---
tip: fonksiyon
kod: "10.01.05-2"
arac: "[[Keşif Teklif]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Teklifi sözleşmeye çevir

> Kod `10.01.05-2` · Araç: [[Keşif Teklif]]

## Ne yapar
- Teklifi sözleşmeye çevir
- Bağlı modül: Birim fiyatlı teklif.

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
