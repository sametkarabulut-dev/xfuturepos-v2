---
tip: fonksiyon
kod: "10.02.04-2"
arac: "[[Ek İş Kaydı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Onaysız ek işleri listele

> Kod `10.02.04-2` · Araç: [[Ek İş Kaydı]]

## Ne yapar
- Onaysız ek işleri listele
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
