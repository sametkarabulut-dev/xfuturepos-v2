---
tip: fonksiyon
kod: "15.07.02-1"
arac: "[[Kurulum Kaydı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kurulum checklist'i çıkar

> Kod `15.07.02-1` · Araç: [[Kurulum Kaydı]]

## Ne yapar
- Kurulum checklist'i çıkar
- Bağlı modül: Kurulum, eğitim ve müşteri ortam kaydı.

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
