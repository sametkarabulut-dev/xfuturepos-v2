---
tip: fonksiyon
kod: "13.03.05-1"
arac: "[[Kapasite Slot]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Perşembe boş slot

> Kod `13.03.05-1` · Araç: [[Kapasite Slot]]

## Ne yapar
- Perşembe boş slot
- Bağlı modül: Haftalık iş kabul slotları

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
