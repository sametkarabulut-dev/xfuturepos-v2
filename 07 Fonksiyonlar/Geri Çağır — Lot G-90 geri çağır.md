---
tip: fonksiyon
kod: "13.05.05-1"
arac: "[[Geri Çağır]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Lot G-90 geri çağır

> Kod `13.05.05-1` · Araç: [[Geri Çağır]]

## Ne yapar
- Lot G-90 geri çağır
- Bağlı modül: Lot bazlı geri çağırma ve müşteri listesi. Çekirdek genişleme: CRM.

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
