---
tip: fonksiyon
kod: "15.06.01-2"
arac: "[[Yayın Masası]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Boş yayın slotlarını listele

> Kod `15.06.01-2` · Araç: [[Yayın Masası]]

## Ne yapar
- Boş yayın slotlarını listele
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
