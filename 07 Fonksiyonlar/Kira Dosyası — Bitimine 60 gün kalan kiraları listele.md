---
tip: fonksiyon
kod: "09.02.01-1"
arac: "[[Kira Dosyası]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bitimine 60 gün kalan kiraları listele

> Kod `09.02.01-1` · Araç: [[Kira Dosyası]]

## Ne yapar
- Bitimine 60 gün kalan kiraları listele
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
