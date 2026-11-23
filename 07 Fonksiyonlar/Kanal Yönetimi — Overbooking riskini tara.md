---
tip: fonksiyon
kod: "09.05.05-2"
arac: "[[Kanal Yönetimi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Overbooking riskini tara

> Kod `09.05.05-2` · Araç: [[Kanal Yönetimi]]

## Ne yapar
- Overbooking riskini tara
- Bağlı modül: OTA/ilan kanallarında takvim/fiyat senkron uyumsuzluk takibi.

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
