---
tip: fonksiyon
kod: "12.03.05-1"
arac: "[[N Belge]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# N2 belgesi bitiş tarihi

> Kod `12.03.05-1` · Araç: [[N Belge]]

## Ne yapar
- N2 belgesi bitiş tarihi
- Bağlı modül: N1/N2 süre ve şube alan uygunluk notu.

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
