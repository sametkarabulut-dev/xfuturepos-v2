---
tip: fonksiyon
kod: "12.02.01-2"
arac: "[[CMR Belgesi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# CMR ye ihtirazi kayıt ekle

> Kod `12.02.01-2` · Araç: [[CMR Belgesi]]

## Ne yapar
- CMR ye ihtirazi kayıt ekle
- Bağlı modül: CMR taşıma senedi alanları ve ihtirazi kayıt; ev eşyası taşınması CMR dışı.

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
