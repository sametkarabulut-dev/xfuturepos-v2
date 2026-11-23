---
tip: fonksiyon
kod: "10.07.05-1"
arac: "[[UYDS Hazırlık]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Aylık seviye paketini hazırla

> Kod `10.07.05-1` · Araç: [[UYDS Hazırlık]]

## Ne yapar
- Aylık seviye paketini hazırla
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
