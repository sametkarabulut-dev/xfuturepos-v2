---
tip: fonksiyon
kod: "16.04.02-2"
arac: "[[Telif bildirim]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Eser listesi eksik sanatçı?

> Kod `16.04.02-2` · Araç: [[Telif bildirim]]

## Ne yapar
- Eser listesi eksik sanatçı?
- Bağlı modül: MESAM-MSG konser/etkinlik lisansı ve eser listesi taslağı.

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
