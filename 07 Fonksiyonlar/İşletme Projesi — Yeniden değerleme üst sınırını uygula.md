---
tip: fonksiyon
kod: "09.03.01-2"
arac: "[[İşletme Projesi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yeniden değerleme üst sınırını uygula

> Kod `09.03.01-2` · Araç: [[İşletme Projesi]]

## Ne yapar
- Yeniden değerleme üst sınırını uygula
- Bağlı modül: Yıllık gelir-gider, avans/aidat dağılımı; geçici proje ve genel kurul onayı.

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
