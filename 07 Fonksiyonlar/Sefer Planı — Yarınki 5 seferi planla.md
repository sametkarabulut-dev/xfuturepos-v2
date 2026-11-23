---
tip: fonksiyon
kod: "12.01.01-1"
arac: "[[Sefer Planı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yarınki 5 seferi planla

> Kod `12.01.01-1` · Araç: [[Sefer Planı]]

## Ne yapar
- Yarınki 5 seferi planla
- Bağlı modül: Güzergâh, yükleme-boşaltma penceresi ve araç-şoför ataması; boş dönüş notu.

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
