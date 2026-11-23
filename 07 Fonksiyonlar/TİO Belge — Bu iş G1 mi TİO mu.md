---
tip: fonksiyon
kod: "12.06.03-2"
arac: "[[TİO Belge]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu iş G1 mi TİO mu

> Kod `12.06.03-2` · Araç: [[TİO Belge]]

## Ne yapar
- Bu iş G1 mi TİO mu
- Bağlı modül: TİO belgesi (eski R1/R2) ve G1 acente ayrımı.

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
