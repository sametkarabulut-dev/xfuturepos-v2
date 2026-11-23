---
tip: fonksiyon
kod: "15.04.03-1"
arac: "[[Hak Listesi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Hak listesi eksik mi?

> Kod `15.04.03-1` · Araç: [[Hak Listesi]]

## Ne yapar
- Hak listesi eksik mi?
- Bağlı modül: Teslimde mali hakların ayrı ayrı gösterildiği kontrol listesi.

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
