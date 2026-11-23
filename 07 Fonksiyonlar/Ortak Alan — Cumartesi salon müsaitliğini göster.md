---
tip: fonksiyon
kod: "09.03.04-1"
arac: "[[Ortak Alan]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Cumartesi salon müsaitliğini göster

> Kod `09.03.04-1` · Araç: [[Ortak Alan]]

## Ne yapar
- Cumartesi salon müsaitliğini göster
- Bağlı modül: Ortak alan (salon, misafir otopark vb.) rezervasyon yönetimi.

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
