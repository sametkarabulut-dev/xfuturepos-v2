---
tip: fonksiyon
kod: "15.02.05-2"
arac: "[[Dönüşüm İzleme]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Son 7 gün dönüşüm düşüşünü özetle

> Kod `15.02.05-2` · Araç: [[Dönüşüm İzleme]]

## Ne yapar
- Son 7 gün dönüşüm düşüşünü özetle
- Bağlı modül: Dönüşüm ve etiket eşleme kontrolü.

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
