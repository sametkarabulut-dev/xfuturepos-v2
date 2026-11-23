---
tip: fonksiyon
kod: "10.00.02-2"
arac: "[[Saha Puantajı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Elektrik ekibi puantajını özetle

> Kod `10.00.02-2` · Araç: [[Saha Puantajı]]

## Ne yapar
- Elektrik ekibi puantajını özetle
- Bağlı modül: Firma-ekip-blok puantaj; Personel genişlemesi. Çekirdek genişleme: Personel & Vardiya.

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
