---
tip: fonksiyon
kod: "15.01.05-1"
arac: "[[Depo Bağlantısı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu PR hangi işe ait?

> Kod `15.01.05-1` · Araç: [[Depo Bağlantısı]]

## Ne yapar
- Bu PR hangi işe ait?
- Bağlı modül: Commit/PR kaydını iş kartına bağlama.

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
