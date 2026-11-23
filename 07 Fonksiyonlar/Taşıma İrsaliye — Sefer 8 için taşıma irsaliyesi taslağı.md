---
tip: fonksiyon
kod: "12.01.05-1"
arac: "[[Taşıma İrsaliye]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Sefer 8 için taşıma irsaliyesi taslağı

> Kod `12.01.05-1` · Araç: [[Taşıma İrsaliye]]

## Ne yapar
- Sefer 8 için taşıma irsaliyesi taslağı
- Bağlı modül: VUK taşıma irsaliyesi alanları; sevk e-irsaliyesi ile karıştırılmaz.

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
