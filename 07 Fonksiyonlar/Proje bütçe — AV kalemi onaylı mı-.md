---
tip: fonksiyon
kod: "16.03.01-2"
arac: "[[Proje bütçe]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# AV kalemi onaylı mı?

> Kod `16.03.01-2` · Araç: [[Proje bütçe]]

## Ne yapar
- AV kalemi onaylı mı?
- Bağlı modül: Kurumsal brief, kalem bütçe ve onay kapıları.

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
