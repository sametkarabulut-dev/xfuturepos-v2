---
tip: fonksiyon
kod: "12.04.02-2"
arac: "[[Kurye Atama]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# En az yüklü kuryeyi öner

> Kod `12.04.02-2` · Araç: [[Kurye Atama]]

## Ne yapar
- En az yüklü kuryeyi öner
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
