---
tip: fonksiyon
kod: "12.02.03-1"
arac: "[[Transit Dosya]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu seferde TIR karne durumu ne

> Kod `12.02.03-1` · Araç: [[Transit Dosya]]

## Ne yapar
- Bu seferde TIR karne durumu ne
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
