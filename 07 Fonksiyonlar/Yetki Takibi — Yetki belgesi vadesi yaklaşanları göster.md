---
tip: fonksiyon
kod: "09.00.04-1"
arac: "[[Yetki Takibi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yetki belgesi vadesi yaklaşanları göster

> Kod `09.00.04-1` · Araç: [[Yetki Takibi]]

## Ne yapar
- Yetki belgesi vadesi yaklaşanları göster
- Bağlı modül: İşletme yetki belgesi, sorumlu emlak danışmanı ve belge vade takibi (TTBS).

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
