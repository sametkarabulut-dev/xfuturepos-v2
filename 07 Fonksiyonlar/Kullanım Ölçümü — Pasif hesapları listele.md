---
tip: fonksiyon
kod: "15.08.05-1"
arac: "[[Kullanım Ölçümü]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Pasif hesapları listele

> Kod `15.08.05-1` · Araç: [[Kullanım Ölçümü]]

## Ne yapar
- Pasif hesapları listele
- Bağlı modül: Ürün kullanım ve aktif hesap özeti.

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
