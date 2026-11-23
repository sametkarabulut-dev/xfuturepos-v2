---
tip: fonksiyon
kod: "12.07.02-1"
arac: "[[Pick Pack]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bugün 40 siparişi kuyruğa al

> Kod `12.07.02-1` · Araç: [[Pick Pack]]

## Ne yapar
- Bugün 40 siparişi kuyruğa al
- Bağlı modül: Sipariş toplama, paketleme ve sevke hazır etme kuyruğu.

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
