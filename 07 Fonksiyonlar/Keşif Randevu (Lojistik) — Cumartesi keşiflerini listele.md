---
tip: fonksiyon
kod: "12.05.01-1"
arac: "[[Keşif Randevu (Lojistik)]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Cumartesi keşiflerini listele

> Kod `12.05.01-1` · Araç: [[Keşif Randevu (Lojistik)]]

## Ne yapar
- Cumartesi keşiflerini listele
- Bağlı modül: Keşif günü, kat, asansör, m²; teklife girdi. CRM çekirdeğine iş akışı bağlar.

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
