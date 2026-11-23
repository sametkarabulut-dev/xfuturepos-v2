---
tip: fonksiyon
kod: "09.00.04-2"
arac: "[[Yetki Takibi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Seviye 5 sorumlu listesi

> Kod `09.00.04-2` · Araç: [[Yetki Takibi]]

## Ne yapar
- Seviye 5 sorumlu listesi
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
