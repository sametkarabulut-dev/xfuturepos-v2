---
tip: fonksiyon
kod: "15.06.01-1"
arac: "[[Yayın Masası]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yarınki yayın sırasını göster

> Kod `15.06.01-1` · Araç: [[Yayın Masası]]

## Ne yapar
- Yarınki yayın sırasını göster
- Bağlı modül: Kendi yayın planı ve boş slot.

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
