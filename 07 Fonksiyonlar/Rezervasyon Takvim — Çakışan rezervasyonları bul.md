---
tip: fonksiyon
kod: "09.05.01-2"
arac: "[[Rezervasyon Takvim]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Çakışan rezervasyonları bul

> Kod `09.05.01-2` · Araç: [[Rezervasyon Takvim]]

## Ne yapar
- Çakışan rezervasyonları bul
- Bağlı modül: Kısa süreli konaklama takvimi, çakışma ve kapalı gün yönetimi.

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
