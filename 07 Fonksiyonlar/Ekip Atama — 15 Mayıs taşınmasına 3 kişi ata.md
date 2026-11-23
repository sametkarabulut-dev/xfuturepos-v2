---
tip: fonksiyon
kod: "12.05.03-1"
arac: "[[Ekip Atama]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# 15 Mayıs taşınmasına 3 kişi ata

> Kod `12.05.03-1` · Araç: [[Ekip Atama]]

## Ne yapar
- 15 Mayıs taşınmasına 3 kişi ata
- Bağlı modül: Taşınma günü kamyon, ekip ve paketleme malzemesi ataması.

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
