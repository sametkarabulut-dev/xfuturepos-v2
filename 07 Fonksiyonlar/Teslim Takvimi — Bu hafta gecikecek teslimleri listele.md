---
tip: fonksiyon
kod: "15.00.04-1"
arac: "[[Teslim Takvimi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu hafta gecikecek teslimleri listele

> Kod `15.00.04-1` · Araç: [[Teslim Takvimi]]

## Ne yapar
- Bu hafta gecikecek teslimleri listele
- Bağlı modül: Teslim tarihleri, bağımlılıklar ve gecikme riski.

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
