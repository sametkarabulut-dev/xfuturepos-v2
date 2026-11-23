---
tip: fonksiyon
kod: "12.02.04-1"
arac: "[[Ro-Ro Slot]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Trieste slotunu bu sevkiyata bağla

> Kod `12.02.04-1` · Araç: [[Ro-Ro Slot]]

## Ne yapar
- Trieste slotunu bu sevkiyata bağla
- Bağlı modül: Feribot/Ro-Ro rezervasyonunu sevkiyat ETA’sına bağlar.

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
