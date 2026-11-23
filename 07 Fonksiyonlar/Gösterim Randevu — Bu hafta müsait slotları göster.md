---
tip: fonksiyon
kod: "09.00.02-1"
arac: "[[Gösterim Randevu]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu hafta müsait slotları göster

> Kod `09.00.02-1` · Araç: [[Gösterim Randevu]]

## Ne yapar
- Bu hafta müsait slotları göster
- Bağlı modül: Mülk gösterimi randevu, çakışma kontrolü ve danışman ataması.

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
