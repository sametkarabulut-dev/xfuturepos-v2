---
tip: fonksiyon
kod: "12.06.01-2"
arac: "[[Taşıyıcı Havuz]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# XYZ Nakliyat ı kara listeye öner

> Kod `12.06.01-2` · Araç: [[Taşıyıcı Havuz]]

## Ne yapar
- XYZ Nakliyat ı kara listeye öner
- Bağlı modül: Alt taşıyıcı yetki belgesi, fiyat ve performans havuzu.

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
