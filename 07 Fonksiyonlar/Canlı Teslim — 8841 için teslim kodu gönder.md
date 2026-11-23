---
tip: fonksiyon
kod: "12.04.03-1"
arac: "[[Canlı Teslim]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# 8841 için teslim kodu gönder

> Kod `12.04.03-1` · Araç: [[Canlı Teslim]]

## Ne yapar
- 8841 için teslim kodu gönder
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
