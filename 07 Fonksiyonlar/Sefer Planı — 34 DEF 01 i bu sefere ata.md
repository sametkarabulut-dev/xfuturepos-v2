---
tip: fonksiyon
kod: "12.01.01-2"
arac: "[[Sefer Planı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# 34 DEF 01 i bu sefere ata

> Kod `12.01.01-2` · Araç: [[Sefer Planı]]

## Ne yapar
- 34 DEF 01 i bu sefere ata
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
