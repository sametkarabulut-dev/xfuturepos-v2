---
tip: fonksiyon
kod: "15.03.05-2"
arac: "[[Etkileşim Özeti]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Düşen kanalları işaretle

> Kod `15.03.05-2` · Araç: [[Etkileşim Özeti]]

## Ne yapar
- Düşen kanalları işaretle
- Bağlı modül: Dönem etkileşim ve müşteri rapor taslağı.

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
