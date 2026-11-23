---
tip: fonksiyon
kod: "09.04.02-2"
arac: "[[Lisans Sicil]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yenileme eğitimi yaklaşanları göster

> Kod `09.04.02-2` · Araç: [[Lisans Sicil]]

## Ne yapar
- Yenileme eğitimi yaklaşanları göster
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
