---
tip: fonksiyon
kod: "16.03.01-1"
arac: "[[Proje bütçe]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Lansman bütçe sapması?

> Kod `16.03.01-1` · Araç: [[Proje bütçe]]

## Ne yapar
- Lansman bütçe sapması?
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
