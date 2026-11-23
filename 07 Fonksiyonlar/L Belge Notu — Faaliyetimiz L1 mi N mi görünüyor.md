---
tip: fonksiyon
kod: "12.07.05-1"
arac: "[[L Belge Notu]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Faaliyetimiz L1 mi N mi görünüyor

> Kod `12.07.05-1` · Araç: [[L Belge Notu]]

## Ne yapar
- Faaliyetimiz L1 mi N mi görünüyor
- Bağlı modül: Depo + dağıtım birlikteyse L1/L2 hatırlatması.

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
