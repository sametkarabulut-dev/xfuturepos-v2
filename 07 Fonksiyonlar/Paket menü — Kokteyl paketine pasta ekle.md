---
tip: fonksiyon
kod: "16.01.02-2"
arac: "[[Paket menü]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kokteyl paketine pasta ekle

> Kod `16.01.02-2` · Araç: [[Paket menü]]

## Ne yapar
- Kokteyl paketine pasta ekle
- Bağlı modül: Kişi başı paket, ek hizmet ve toplam tutar.

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
