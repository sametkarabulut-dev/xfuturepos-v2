---
tip: fonksiyon
kod: "12.00.02-2"
arac: "[[Navlun Teklifi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Geçen ayki ABC fiyatını bu işe kopyala

> Kod `12.00.02-2` · Araç: [[Navlun Teklifi]]

## Ne yapar
- Geçen ayki ABC fiyatını bu işe kopyala
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
