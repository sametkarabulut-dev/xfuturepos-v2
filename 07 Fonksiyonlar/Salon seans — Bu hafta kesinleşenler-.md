---
tip: fonksiyon
kod: "16.01.01-2"
arac: "[[Salon seans]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu hafta kesinleşenler?

> Kod `16.01.01-2` · Araç: [[Salon seans]]

## Ne yapar
- Bu hafta kesinleşenler?
- Bağlı modül: Çoklu salon ve öğle/akşam seans rezervasyonu; sözün kayda bağlanması.

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
