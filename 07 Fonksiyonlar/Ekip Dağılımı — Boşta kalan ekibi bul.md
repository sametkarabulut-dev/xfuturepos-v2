---
tip: fonksiyon
kod: "10.02.03-2"
arac: "[[Ekip Dağılımı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Boşta kalan ekibi bul

> Kod `10.02.03-2` · Araç: [[Ekip Dağılımı]]

## Ne yapar
- Boşta kalan ekibi bul
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
