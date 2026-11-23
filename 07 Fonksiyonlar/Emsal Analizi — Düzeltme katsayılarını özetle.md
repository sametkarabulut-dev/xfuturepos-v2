---
tip: fonksiyon
kod: "09.04.04-2"
arac: "[[Emsal Analizi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Düzeltme katsayılarını özetle

> Kod `09.04.04-2` · Araç: [[Emsal Analizi]]

## Ne yapar
- Düzeltme katsayılarını özetle
- Bağlı modül: Karşılaştırılabilir satış/kira emsal tablosu ve düzeltme önerileri.

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
