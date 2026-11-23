---
tip: fonksiyon
kod: "15.06.02-2"
arac: "[[İlan Envanteri]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu hafta satılan ilanları özetle

> Kod `15.06.02-2` · Araç: [[İlan Envanteri]]

## Ne yapar
- Bu hafta satılan ilanları özetle
- Bağlı modül: Kendi alan/zaman envanteri ve satış kaydı.

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
