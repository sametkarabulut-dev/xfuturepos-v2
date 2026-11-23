---
tip: fonksiyon
kod: "10.04.03-2"
arac: "[[İş Takvimi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Çakışan işleri bul

> Kod `10.04.03-2` · Araç: [[İş Takvimi]]

## Ne yapar
- Çakışan işleri bul
- Bağlı modül: Usta ve malzeme günleri.

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
