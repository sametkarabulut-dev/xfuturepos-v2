---
tip: fonksiyon
kod: "10.01.05-1"
arac: "[[Keşif Teklif]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Villaya teklif hazırla

> Kod `10.01.05-1` · Araç: [[Keşif Teklif]]

## Ne yapar
- Villaya teklif hazırla
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
