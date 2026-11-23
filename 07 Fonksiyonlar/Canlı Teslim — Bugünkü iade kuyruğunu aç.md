---
tip: fonksiyon
kod: "12.04.03-2"
arac: "[[Canlı Teslim]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bugünkü iade kuyruğunu aç

> Kod `12.04.03-2` · Araç: [[Canlı Teslim]]

## Ne yapar
- Bugünkü iade kuyruğunu aç
- Bağlı modül: Teslim kodu/link, red ve iade akışı.

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
