---
tip: fonksiyon
kod: "09.03.02-2"
arac: "[[Genel Kurul]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yönetim planı değişiklik gündemi hazırla

> Kod `09.03.02-2` · Araç: [[Genel Kurul]]

## Ne yapar
- Yönetim planı değişiklik gündemi hazırla
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
