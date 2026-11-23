---
tip: fonksiyon
kod: "10.06.03-1"
arac: "[[Müellif Teslim]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# YDK’ye proje teslim et

> Kod `10.06.03-1` · Araç: [[Müellif Teslim]]

## Ne yapar
- YDK’ye proje teslim et
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
