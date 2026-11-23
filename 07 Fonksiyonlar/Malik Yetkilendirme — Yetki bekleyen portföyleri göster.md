---
tip: fonksiyon
kod: "09.01.02-1"
arac: "[[Malik Yetkilendirme]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yetki bekleyen portföyleri göster

> Kod `09.01.02-1` · Araç: [[Malik Yetkilendirme]]

## Ne yapar
- Yetki bekleyen portföyleri göster
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
