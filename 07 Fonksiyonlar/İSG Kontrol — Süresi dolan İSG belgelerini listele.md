---
tip: fonksiyon
kod: "10.00.06-1"
arac: "[[İSG Kontrol]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Süresi dolan İSG belgelerini listele

> Kod `10.00.06-1` · Araç: [[İSG Kontrol]]

## Ne yapar
- Süresi dolan İSG belgelerini listele
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
