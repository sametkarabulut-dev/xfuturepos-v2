---
tip: fonksiyon
kod: "09.01.03-2"
arac: "[[Teklif Takibi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu portföyün son teklifini özetle

> Kod `09.01.03-2` · Araç: [[Teklif Takibi]]

## Ne yapar
- Bu portföyün son teklifini özetle
- Bağlı modül: Alıcı teklifleri, karşı teklif ve durum pipeline'ı.

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
