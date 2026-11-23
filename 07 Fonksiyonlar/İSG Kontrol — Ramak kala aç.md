---
tip: fonksiyon
kod: "10.00.06-2"
arac: "[[İSG Kontrol]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Ramak kala aç

> Kod `10.00.06-2` · Araç: [[İSG Kontrol]]

## Ne yapar
- Ramak kala aç
- Bağlı modül: SGP, KKD, ramak kala, belge süresi. Çekirdek genişleme: Personel & Vardiya.

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
