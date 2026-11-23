---
tip: fonksiyon
kod: "13.05.03-1"
arac: "[[Kayıt Onay]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kayıt belgesi bitiş tarihi

> Kod `13.05.03-1` · Araç: [[Kayıt Onay]]

## Ne yapar
- Kayıt belgesi bitiş tarihi
- Bağlı modül: İşletme kayıt/onay belgesi hatırlatıcı; tam HACCP suite değil

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
