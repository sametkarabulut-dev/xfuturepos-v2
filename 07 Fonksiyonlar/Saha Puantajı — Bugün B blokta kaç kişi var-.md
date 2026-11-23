---
tip: fonksiyon
kod: "10.00.02-1"
arac: "[[Saha Puantajı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bugün B blokta kaç kişi var?

> Kod `10.00.02-1` · Araç: [[Saha Puantajı]]

## Ne yapar
- Bugün B blokta kaç kişi var?
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
