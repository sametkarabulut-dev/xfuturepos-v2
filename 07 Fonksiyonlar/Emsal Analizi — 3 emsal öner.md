---
tip: fonksiyon
kod: "09.04.04-1"
arac: "[[Emsal Analizi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# 3 emsal öner

> Kod `09.04.04-1` · Araç: [[Emsal Analizi]]

## Ne yapar
- 3 emsal öner
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
