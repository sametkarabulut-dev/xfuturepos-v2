---
tip: fonksiyon
kod: "13.06.02-1"
arac: "[[Dönüş Kabul]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# ABC dönüşünü kaydet 960 adet

> Kod `13.06.02-1` · Araç: [[Dönüş Kabul]]

## Ne yapar
- ABC dönüşünü kaydet 960 adet
- Bağlı modül: Mamul kabul/ret ve reçete tüketim düşümü

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
