---
tip: fonksiyon
kod: "16.04.02-1"
arac: "[[Telif bildirim]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# MSG bildirim taslağı hazırla

> Kod `16.04.02-1` · Araç: [[Telif bildirim]]

## Ne yapar
- MSG bildirim taslağı hazırla
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
