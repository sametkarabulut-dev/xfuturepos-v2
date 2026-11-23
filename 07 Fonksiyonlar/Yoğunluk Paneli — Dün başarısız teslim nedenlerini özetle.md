---
tip: fonksiyon
kod: "12.04.05-1"
arac: "[[Yoğunluk Paneli]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Dün başarısız teslim nedenlerini özetle

> Kod `12.04.05-1` · Araç: [[Yoğunluk Paneli]]

## Ne yapar
- Dün başarısız teslim nedenlerini özetle
- Bağlı modül: Saat dilimine göre başarısız teslim ve neden özeti.

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
