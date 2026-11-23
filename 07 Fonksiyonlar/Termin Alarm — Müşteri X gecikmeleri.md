---
tip: fonksiyon
kod: "13.01.03-2"
arac: "[[Termin Alarm]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Müşteri X gecikmeleri

> Kod `13.01.03-2` · Araç: [[Termin Alarm]]

## Ne yapar
- Müşteri X gecikmeleri
- Bağlı modül: Teslim riski ve dar boğaz uyarısı. Çekirdek genişleme: CRM.

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
