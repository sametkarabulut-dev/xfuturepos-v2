---
tip: fonksiyon
kod: "10.02.03-1"
arac: "[[Ekip Dağılımı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yarın 4 ustayı D şantiyesine kaydır

> Kod `10.02.03-1` · Araç: [[Ekip Dağılımı]]

## Ne yapar
- Yarın 4 ustayı D şantiyesine kaydır
- Bağlı modül: Ekip-şantiye ataması. Çekirdek genişleme: Personel & Vardiya.

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
