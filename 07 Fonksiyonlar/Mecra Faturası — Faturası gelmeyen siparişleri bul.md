---
tip: fonksiyon
kod: "15.05.03-1"
arac: "[[Mecra Faturası]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Faturası gelmeyen siparişleri bul

> Kod `15.05.03-1` · Araç: [[Mecra Faturası]]

## Ne yapar
- Faturası gelmeyen siparişleri bul
- Bağlı modül: Mecra faturası ile plan/sipariş satırı eşlemesi.

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
