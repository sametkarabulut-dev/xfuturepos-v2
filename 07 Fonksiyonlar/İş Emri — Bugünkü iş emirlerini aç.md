---
tip: fonksiyon
kod: "10.02.01-1"
arac: "[[İş Emri]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bugünkü iş emirlerini aç

> Kod `10.02.01-1` · Araç: [[İş Emri]]

## Ne yapar
- Bugünkü iş emirlerini aç
- Bağlı modül: Mahal/poz iş emri.

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
