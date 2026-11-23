---
tip: fonksiyon
kod: "15.00.02-1"
arac: "[[Saat Kullanımı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu haftanın faturalanamayan saatini özetle

> Kod `15.00.02-1` · Araç: [[Saat Kullanımı]]

## Ne yapar
- Bu haftanın faturalanamayan saatini özetle
- Bağlı modül: Faturalanabilir ve faturalanamayan saat kaydı; proje veya retainer ile eşleme.

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
