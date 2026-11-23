---
tip: fonksiyon
kod: "15.00.07-1"
arac: "[[Teklif Paketi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Benzer tekliften taslak üret

> Kod `15.00.07-1` · Araç: [[Teklif Paketi]]

## Ne yapar
- Benzer tekliften taslak üret
- Bağlı modül: Teklif şablonu, kalem ve süre varsayımları.

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
