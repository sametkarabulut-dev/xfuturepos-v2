---
tip: fonksiyon
kod: "09.03.04-2"
arac: "[[Ortak Alan]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Çakışan rezervasyonları bul

> Kod `09.03.04-2` · Araç: [[Ortak Alan]]

## Ne yapar
- Çakışan rezervasyonları bul
- Bağlı modül: Ortak alan (salon, misafir otopark vb.) rezervasyon yönetimi.

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
