---
tip: fonksiyon
kod: "13.00.03-1"
arac: "[[Fire Kayıt]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# İş emri 88 fire kaydet 12 adet

> Kod `13.00.03-1` · Araç: [[Fire Kayıt]]

## Ne yapar
- İş emri 88 fire kaydet 12 adet
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
