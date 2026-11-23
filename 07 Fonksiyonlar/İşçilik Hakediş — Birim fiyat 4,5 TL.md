---
tip: fonksiyon
kod: "13.03.02-2"
arac: "[[İşçilik Hakediş]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Birim fiyat 4,5 TL

> Kod `13.03.02-2` · Araç: [[İşçilik Hakediş]]

## Ne yapar
- Birim fiyat 4,5 TL
- Bağlı modül: Kabul adedi üzerinden işçilik faturalama. Çekirdek genişleme: e-Fatura/e-Arşiv.

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
