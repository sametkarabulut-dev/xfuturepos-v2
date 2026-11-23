---
tip: fonksiyon
kod: "13.00.02-2"
arac: "[[Reçete BOM]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Fire oranını yüzde 5 yap

> Kod `13.00.02-2` · Araç: [[Reçete BOM]]

## Ne yapar
- Fire oranını yüzde 5 yap
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
