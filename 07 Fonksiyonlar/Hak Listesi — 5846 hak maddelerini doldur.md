---
tip: fonksiyon
kod: "15.04.03-2"
arac: "[[Hak Listesi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# 5846 hak maddelerini doldur

> Kod `15.04.03-2` · Araç: [[Hak Listesi]]

## Ne yapar
- 5846 hak maddelerini doldur
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
