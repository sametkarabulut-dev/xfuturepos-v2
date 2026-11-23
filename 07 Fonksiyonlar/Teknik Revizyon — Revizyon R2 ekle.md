---
tip: fonksiyon
kod: "13.04.04-1"
arac: "[[Teknik Revizyon]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Revizyon R2 ekle

> Kod `13.04.04-1` · Araç: [[Teknik Revizyon]]

## Ne yapar
- Revizyon R2 ekle
- Bağlı modül: Müşteri çizim değişikliği kaydı. Çekirdek genişleme: CRM.

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
