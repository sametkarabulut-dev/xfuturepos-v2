---
tip: fonksiyon
kod: "15.04.01-1"
arac: "[[Varlık Sürümü]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Final sürümü bul

> Kod `15.04.01-1` · Araç: [[Varlık Sürümü]]

## Ne yapar
- Final sürümü bul
- Bağlı modül: Dosya sürümü, final ve müşteri klasörü.

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
