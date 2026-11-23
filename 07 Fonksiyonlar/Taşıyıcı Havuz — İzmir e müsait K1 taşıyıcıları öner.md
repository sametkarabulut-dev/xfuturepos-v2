---
tip: fonksiyon
kod: "12.06.01-1"
arac: "[[Taşıyıcı Havuz]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# İzmir e müsait K1 taşıyıcıları öner

> Kod `12.06.01-1` · Araç: [[Taşıyıcı Havuz]]

## Ne yapar
- İzmir e müsait K1 taşıyıcıları öner
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
