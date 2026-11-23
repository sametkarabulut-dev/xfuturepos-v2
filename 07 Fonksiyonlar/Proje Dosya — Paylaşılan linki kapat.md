---
tip: fonksiyon
kod: "10.06.01-2"
arac: "[[Proje Dosya]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Paylaşılan linki kapat

> Kod `10.06.01-2` · Araç: [[Proje Dosya]]

## Ne yapar
- Paylaşılan linki kapat
- Bağlı modül: Disiplin dosya ağacı.

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
