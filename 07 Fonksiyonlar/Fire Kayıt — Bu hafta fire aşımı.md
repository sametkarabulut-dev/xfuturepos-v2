---
tip: fonksiyon
kod: "13.00.03-2"
arac: "[[Fire Kayıt]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu hafta fire aşımı

> Kod `13.00.03-2` · Araç: [[Fire Kayıt]]

## Ne yapar
- Bu hafta fire aşımı
- Bağlı modül: İş emri bazlı fire; reçete toleransı ile gerçekleşen karşılaştırma

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
