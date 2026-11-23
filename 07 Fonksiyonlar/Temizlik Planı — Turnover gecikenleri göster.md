---
tip: fonksiyon
kod: "09.05.04-2"
arac: "[[Temizlik Planı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Turnover gecikenleri göster

> Kod `09.05.04-2` · Araç: [[Temizlik Planı]]

## Ne yapar
- Turnover gecikenleri göster
- Bağlı modül: Personel & Vardiya genişlemesi: çıkış sonrası temizlik ve turnover planı.

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
