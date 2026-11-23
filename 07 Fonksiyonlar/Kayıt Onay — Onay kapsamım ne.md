---
tip: fonksiyon
kod: "13.05.03-2"
arac: "[[Kayıt Onay]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Onay kapsamım ne

> Kod `13.05.03-2` · Araç: [[Kayıt Onay]]

## Ne yapar
- Onay kapsamım ne
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
