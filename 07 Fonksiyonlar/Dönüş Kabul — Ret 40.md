---
tip: fonksiyon
kod: "13.06.02-2"
arac: "[[Dönüş Kabul]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Ret 40

> Kod `13.06.02-2` · Araç: [[Dönüş Kabul]]

## Ne yapar
- Ret 40
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
