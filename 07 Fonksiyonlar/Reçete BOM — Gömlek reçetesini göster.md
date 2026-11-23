---
tip: fonksiyon
kod: "13.00.02-1"
arac: "[[Reçete BOM]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Gömlek reçetesini göster

> Kod `13.00.02-1` · Araç: [[Reçete BOM]]

## Ne yapar
- Gömlek reçetesini göster
- Bağlı modül: Hammadde, birim, beklenen fire oranı; iş emrine bağlanır

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
