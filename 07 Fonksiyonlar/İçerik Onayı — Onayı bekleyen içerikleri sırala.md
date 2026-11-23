---
tip: fonksiyon
kod: "15.03.02-1"
arac: "[[İçerik Onayı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Onayı bekleyen içerikleri sırala

> Kod `15.03.02-1` · Araç: [[İçerik Onayı]]

## Ne yapar
- Onayı bekleyen içerikleri sırala
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
