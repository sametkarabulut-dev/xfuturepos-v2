---
tip: fonksiyon
kod: "12.07.02-2"
arac: "[[Pick Pack]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Eksik stoklu siparişleri göster

> Kod `12.07.02-2` · Araç: [[Pick Pack]]

## Ne yapar
- Eksik stoklu siparişleri göster
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
