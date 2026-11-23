---
tip: fonksiyon
kod: "16.02.01-1"
arac: "[[İş brief]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kına brief'i özetle

> Kod `16.02.01-1` · Araç: [[İş brief]]

## Ne yapar
- Kına brief'i özetle
- Bağlı modül: Mekânsız planlayıcı iş dosyası: brief, bütçe, karar sahibi.

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
