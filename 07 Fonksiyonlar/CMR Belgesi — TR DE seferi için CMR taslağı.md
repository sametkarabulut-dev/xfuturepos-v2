---
tip: fonksiyon
kod: "12.02.01-1"
arac: "[[CMR Belgesi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# TR DE seferi için CMR taslağı

> Kod `12.02.01-1` · Araç: [[CMR Belgesi]]

## Ne yapar
- TR DE seferi için CMR taslağı
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
