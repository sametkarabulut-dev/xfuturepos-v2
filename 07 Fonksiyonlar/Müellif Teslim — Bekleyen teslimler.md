---
tip: fonksiyon
kod: "10.06.03-2"
arac: "[[Müellif Teslim]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bekleyen teslimler

> Kod `10.06.03-2` · Araç: [[Müellif Teslim]]

## Ne yapar
- Bekleyen teslimler
- Bağlı modül: YDK/idare teslim tutanağı.

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
