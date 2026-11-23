---
tip: fonksiyon
kod: "09.04.02-1"
arac: "[[Lisans Sicil]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Askı riski olan lisansları listele

> Kod `09.04.02-1` · Araç: [[Lisans Sicil]]

## Ne yapar
- Askı riski olan lisansları listele
- Bağlı modül: Uzman/yardımcı SPL lisans durumu ve yenileme eğitim takibi.

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
