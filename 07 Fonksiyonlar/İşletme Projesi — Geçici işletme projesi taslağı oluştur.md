---
tip: fonksiyon
kod: "09.03.01-1"
arac: "[[İşletme Projesi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Geçici işletme projesi taslağı oluştur

> Kod `09.03.01-1` · Araç: [[İşletme Projesi]]

## Ne yapar
- Geçici işletme projesi taslağı oluştur
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
