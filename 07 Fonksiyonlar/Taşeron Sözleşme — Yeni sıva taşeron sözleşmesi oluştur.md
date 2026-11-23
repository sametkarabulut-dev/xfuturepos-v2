---
tip: fonksiyon
kod: "10.00.07-1"
arac: "[[Taşeron Sözleşme]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yeni sıva taşeron sözleşmesi oluştur

> Kod `10.00.07-1` · Araç: [[Taşeron Sözleşme]]

## Ne yapar
- Yeni sıva taşeron sözleşmesi oluştur
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
