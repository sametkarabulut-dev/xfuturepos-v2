---
tip: fonksiyon
kod: "10.07.05-2"
arac: "[[UYDS Hazırlık]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Eksik UYDS alanları

> Kod `10.07.05-2` · Araç: [[UYDS Hazırlık]]

## Ne yapar
- Eksik UYDS alanları
- Bağlı modül: Resmî giriş için veri paketleme; API iddiasız.

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
