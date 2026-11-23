---
tip: fonksiyon
kod: "13.01.02-2"
arac: "[[Atölye Kuyruk]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Acil işi öne al

> Kod `13.01.02-2` · Araç: [[Atölye Kuyruk]]

## Ne yapar
- Acil işi öne al
- Bağlı modül: Termin öncelikli basit iş sırası

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
