---
tip: fonksiyon
kod: "12.00.06-1"
arac: "[[Hasar Dosyası]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Sevkiyat 441 için hasar dosyası aç

> Kod `12.00.06-1` · Araç: [[Hasar Dosyası]]

## Ne yapar
- Sevkiyat 441 için hasar dosyası aç
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
