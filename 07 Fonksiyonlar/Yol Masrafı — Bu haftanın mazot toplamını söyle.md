---
tip: fonksiyon
kod: "12.01.03-2"
arac: "[[Yol Masrafı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu haftanın mazot toplamını söyle

> Kod `12.01.03-2` · Araç: [[Yol Masrafı]]

## Ne yapar
- Bu haftanın mazot toplamını söyle
- Bağlı modül: Mazot, köprü, bekleme masraflarını sefere bağlayıp kârlılık taslağı üretir.

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
