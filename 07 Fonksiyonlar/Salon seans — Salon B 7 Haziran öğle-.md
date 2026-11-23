---
tip: fonksiyon
kod: "16.01.01-1"
arac: "[[Salon seans]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Salon B 7 Haziran öğle?

> Kod `16.01.01-1` · Araç: [[Salon seans]]

## Ne yapar
- Salon B 7 Haziran öğle?
- Bağlı modül: Çoklu salon ve öğle/akşam seans rezervasyonu; sözün kayda bağlanması.

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
