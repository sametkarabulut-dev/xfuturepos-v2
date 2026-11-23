---
tip: fonksiyon
kod: "12.01.05-2"
arac: "[[Taşıma İrsaliye]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bugün irsaliyesiz kalkan seferler

> Kod `12.01.05-2` · Araç: [[Taşıma İrsaliye]]

## Ne yapar
- Bugün irsaliyesiz kalkan seferler
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
