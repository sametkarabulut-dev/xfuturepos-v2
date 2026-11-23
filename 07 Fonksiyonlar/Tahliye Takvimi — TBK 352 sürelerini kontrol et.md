---
tip: fonksiyon
kod: "09.02.04-2"
arac: "[[Tahliye Takvimi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# TBK 352 sürelerini kontrol et

> Kod `09.02.04-2` · Araç: [[Tahliye Takvimi]]

## Ne yapar
- TBK 352 sürelerini kontrol et
- Bağlı modül: Tahliye taahhüdü tarihleri ve yasal süre hatırlatmaları.

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
