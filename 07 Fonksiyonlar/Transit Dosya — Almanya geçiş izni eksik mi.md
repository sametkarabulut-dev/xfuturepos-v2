---
tip: fonksiyon
kod: "12.02.03-2"
arac: "[[Transit Dosya]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Almanya geçiş izni eksik mi

> Kod `12.02.03-2` · Araç: [[Transit Dosya]]

## Ne yapar
- Almanya geçiş izni eksik mi
- Bağlı modül: TIR karne / NCTS / geçiş izni checklist; hangisinin kullanılacağı güzergâha bağlı.

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
