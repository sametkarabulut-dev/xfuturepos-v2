---
tip: fonksiyon
kod: "16.00.01-2"
arac: "[[Etkinlik takvimi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Aynı tarihe iki opsiyon var mı?

> Kod `16.00.01-2` · Araç: [[Etkinlik takvimi]]

## Ne yapar
- Aynı tarihe iki opsiyon var mı?
- Bağlı modül: Tarih/seans/kaynak doluluğu; opsiyon ve kesin kayıt; çakışma engeli.

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
