---
tip: fonksiyon
kod: "09.03.02-1"
arac: "[[Genel Kurul]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Son kurul kararlarını özetle

> Kod `09.03.02-1` · Araç: [[Genel Kurul]]

## Ne yapar
- Son kurul kararlarını özetle
- Bağlı modül: Toplantı çağrısı, gündem, karar ve tutanak arşivi.

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
