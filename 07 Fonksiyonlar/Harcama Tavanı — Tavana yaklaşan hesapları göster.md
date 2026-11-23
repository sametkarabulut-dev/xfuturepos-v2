---
tip: fonksiyon
kod: "15.02.02-1"
arac: "[[Harcama Tavanı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Tavana yaklaşan hesapları göster

> Kod `15.02.02-1` · Araç: [[Harcama Tavanı]]

## Ne yapar
- Tavana yaklaşan hesapları göster
- Bağlı modül: Bütçe ve spend cap / paylaşılan kredi hattı tavanı izleme.

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
