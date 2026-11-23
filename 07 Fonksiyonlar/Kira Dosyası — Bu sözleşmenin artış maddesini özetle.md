---
tip: fonksiyon
kod: "09.02.01-2"
arac: "[[Kira Dosyası]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu sözleşmenin artış maddesini özetle

> Kod `09.02.01-2` · Araç: [[Kira Dosyası]]

## Ne yapar
- Bu sözleşmenin artış maddesini özetle
- Bağlı modül: Kira sözleşmesi, süre, artış ve eklerin dosya bazlı yönetimi.

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
