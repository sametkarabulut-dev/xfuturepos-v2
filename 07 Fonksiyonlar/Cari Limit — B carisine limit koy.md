---
tip: fonksiyon
kod: "10.05.05-2"
arac: "[[Cari Limit]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# B carisine limit koy

> Kod `10.05.05-2` · Araç: [[Cari Limit]]

## Ne yapar
- B carisine limit koy
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
