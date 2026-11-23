---
tip: fonksiyon
kod: "09.05.01-1"
arac: "[[Rezervasyon Takvim]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu hafta doluluk göster

> Kod `09.05.01-1` · Araç: [[Rezervasyon Takvim]]

## Ne yapar
- Bu hafta doluluk göster
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
