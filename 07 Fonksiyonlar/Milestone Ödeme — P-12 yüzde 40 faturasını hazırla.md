---
tip: fonksiyon
kod: "13.04.03-1"
arac: "[[Milestone Ödeme]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# P-12 yüzde 40 faturasını hazırla

> Kod `13.04.03-1` · Araç: [[Milestone Ödeme]]

## Ne yapar
- P-12 yüzde 40 faturasını hazırla
- Bağlı modül: Proje hakediş basamakları. Çekirdek genişleme: Muhasebe & Gelir-Gider.

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
