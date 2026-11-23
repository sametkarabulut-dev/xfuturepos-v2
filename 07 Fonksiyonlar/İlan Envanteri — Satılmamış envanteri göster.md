---
tip: fonksiyon
kod: "15.06.02-1"
arac: "[[İlan Envanteri]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Satılmamış envanteri göster

> Kod `15.06.02-1` · Araç: [[İlan Envanteri]]

## Ne yapar
- Satılmamış envanteri göster
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
