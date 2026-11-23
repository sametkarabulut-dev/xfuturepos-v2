---
tip: fonksiyon
kod: "15.05.03-2"
arac: "[[Mecra Faturası]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Fatura farklarını listele

> Kod `15.05.03-2` · Araç: [[Mecra Faturası]]

## Ne yapar
- Fatura farklarını listele
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
