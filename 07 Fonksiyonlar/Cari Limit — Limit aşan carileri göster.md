---
tip: fonksiyon
kod: "10.05.05-1"
arac: "[[Cari Limit]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Limit aşan carileri göster

> Kod `10.05.05-1` · Araç: [[Cari Limit]]

## Ne yapar
- Limit aşan carileri göster
- Bağlı modül: Risk limiti/vade. Çekirdek genişleme: Muhasebe.

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
