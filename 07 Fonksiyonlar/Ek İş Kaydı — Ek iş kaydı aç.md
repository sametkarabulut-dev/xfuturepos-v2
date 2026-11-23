---
tip: fonksiyon
kod: "10.02.04-1"
arac: "[[Ek İş Kaydı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Ek iş kaydı aç

> Kod `10.02.04-1` · Araç: [[Ek İş Kaydı]]

## Ne yapar
- Ek iş kaydı aç
- Bağlı modül: Yazılı ek iş/revizyon.

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
