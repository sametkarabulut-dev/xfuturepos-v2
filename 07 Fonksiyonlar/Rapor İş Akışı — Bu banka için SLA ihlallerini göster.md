---
tip: fonksiyon
kod: "09.04.01-2"
arac: "[[Rapor İş Akışı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu banka için SLA ihlallerini göster

> Kod `09.04.01-2` · Araç: [[Rapor İş Akışı]]

## Ne yapar
- Bu banka için SLA ihlallerini göster
- Bağlı modül: Sipariş → saha → taslak → sorumlu imza → teslim pipeline'ı.

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
