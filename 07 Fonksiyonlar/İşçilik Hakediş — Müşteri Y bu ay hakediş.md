---
tip: fonksiyon
kod: "13.03.02-1"
arac: "[[İşçilik Hakediş]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Müşteri Y bu ay hakediş

> Kod `13.03.02-1` · Araç: [[İşçilik Hakediş]]

## Ne yapar
- Müşteri Y bu ay hakediş
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
