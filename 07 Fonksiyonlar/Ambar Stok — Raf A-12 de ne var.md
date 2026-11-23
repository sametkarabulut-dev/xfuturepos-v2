---
tip: fonksiyon
kod: "12.03.03-1"
arac: "[[Ambar Stok]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Raf A-12 de ne var

> Kod `12.03.03-1` · Araç: [[Ambar Stok]]

## Ne yapar
- Raf A-12 de ne var
- Bağlı modül: Kapalı ambar giriş-çıkış, göz/yer ve bekleyen parça arama.

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
