---
tip: fonksiyon
kod: "16.02.01-2"
arac: "[[İş brief]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bütçe tavanı aşıldı mı?

> Kod `16.02.01-2` · Araç: [[İş brief]]

## Ne yapar
- Bütçe tavanı aşıldı mı?
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
