---
tip: fonksiyon
kod: "12.00.02-1"
arac: "[[Navlun Teklifi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# İstanbul Ankara 12 ton navlun taslağı çıkar

> Kod `12.00.02-1` · Araç: [[Navlun Teklifi]]

## Ne yapar
- İstanbul Ankara 12 ton navlun taslağı çıkar
- Bağlı modül: Tonaj, güzergâh ve bekleme ile navlun taslağı; müşteriye göndermeden önce insan onayı.

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
