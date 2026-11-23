---
tip: fonksiyon
kod: "12.04.02-1"
arac: "[[Kurye Atama]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kadıköy bölgesine 2 kurye ata

> Kod `12.04.02-1` · Araç: [[Kurye Atama]]

## Ne yapar
- Kadıköy bölgesine 2 kurye ata
- Bağlı modül: Bölge ve kapasiteye göre kurye/araç ataması. Personel çekirdeği genişlemesi.

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
