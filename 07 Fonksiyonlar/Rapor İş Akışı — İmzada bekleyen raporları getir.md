---
tip: fonksiyon
kod: "09.04.01-1"
arac: "[[Rapor İş Akışı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# İmzada bekleyen raporları getir

> Kod `09.04.01-1` · Araç: [[Rapor İş Akışı]]

## Ne yapar
- İmzada bekleyen raporları getir
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
