---
tip: fonksiyon
kod: "15.02.02-2"
arac: "[[Harcama Tavanı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Dün tavanı aşanları listele

> Kod `15.02.02-2` · Araç: [[Harcama Tavanı]]

## Ne yapar
- Dün tavanı aşanları listele
- Bağlı modül: Bütçe ve spend cap / paylaşılan kredi hattı tavanı izleme.

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
