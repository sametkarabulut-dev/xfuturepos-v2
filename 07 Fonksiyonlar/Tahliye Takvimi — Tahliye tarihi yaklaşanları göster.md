---
tip: fonksiyon
kod: "09.02.04-1"
arac: "[[Tahliye Takvimi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Tahliye tarihi yaklaşanları göster

> Kod `09.02.04-1` · Araç: [[Tahliye Takvimi]]

## Ne yapar
- Tahliye tarihi yaklaşanları göster
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
