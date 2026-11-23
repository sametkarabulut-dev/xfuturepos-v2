---
tip: fonksiyon
kod: "12.00.06-2"
arac: "[[Hasar Dosyası]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Açık hasar dosyalarını özetle

> Kod `12.00.06-2` · Araç: [[Hasar Dosyası]]

## Ne yapar
- Açık hasar dosyalarını özetle
- Bağlı modül: Hasar/kayıp dosyası, tutanak ve sigorta iletim checklisti; tazminat ödemesi AI onayı olmadan yok.

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
