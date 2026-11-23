---
tip: fonksiyon
kod: "13.02.04-1"
arac: "[[Verim Rapor]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# SKU-B verim raporu

> Kod `13.02.04-1` · Araç: [[Verim Rapor]]

## Ne yapar
- SKU-B verim raporu
- Bağlı modül: Plan vs üretilen vs fire. Çekirdek genişleme: Raporlar.

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
