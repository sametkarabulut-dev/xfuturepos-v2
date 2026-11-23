---
tip: fonksiyon
kod: "13.01.02-1"
arac: "[[Atölye Kuyruk]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Torna kuyruğunu sırala

> Kod `13.01.02-1` · Araç: [[Atölye Kuyruk]]

## Ne yapar
- Torna kuyruğunu sırala
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
