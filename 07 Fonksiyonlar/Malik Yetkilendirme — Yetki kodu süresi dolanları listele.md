---
tip: fonksiyon
kod: "09.01.02-2"
arac: "[[Malik Yetkilendirme]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yetki kodu süresi dolanları listele

> Kod `09.01.02-2` · Araç: [[Malik Yetkilendirme]]

## Ne yapar
- Yetki kodu süresi dolanları listele
- Bağlı modül: Malikin e-Devlet üzerinden emlak işletmesine verdiği ilan yetkisinin takip kaydı.

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
