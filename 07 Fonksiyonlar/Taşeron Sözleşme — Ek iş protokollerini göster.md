---
tip: fonksiyon
kod: "10.00.07-2"
arac: "[[Taşeron Sözleşme]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Ek iş protokollerini göster

> Kod `10.00.07-2` · Araç: [[Taşeron Sözleşme]]

## Ne yapar
- Ek iş protokollerini göster
- Bağlı modül: Kapsam, birim fiyat, ölçüm, teminat, ek iş. Çekirdek genişleme: CRM.

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
