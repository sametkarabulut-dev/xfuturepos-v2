---
tip: fonksiyon
kod: "15.00.07-2"
arac: "[[Teklif Paketi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kapsam maddelerini numaralandır

> Kod `15.00.07-2` · Araç: [[Teklif Paketi]]

## Ne yapar
- Kapsam maddelerini numaralandır
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
