---
tip: fonksiyon
kod: "09.05.04-1"
arac: "[[Temizlik Planı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bugünkü temizlik turunu planla

> Kod `09.05.04-1` · Araç: [[Temizlik Planı]]

## Ne yapar
- Bugünkü temizlik turunu planla
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
