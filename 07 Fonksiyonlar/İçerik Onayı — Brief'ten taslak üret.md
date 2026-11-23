---
tip: fonksiyon
kod: "15.03.02-2"
arac: "[[İçerik Onayı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Brief'ten taslak üret

> Kod `15.03.02-2` · Araç: [[İçerik Onayı]]

## Ne yapar
- Brief'ten taslak üret
- Bağlı modül: Brief'ten taslağa ve müşteri onayına giden kuyruk.

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
