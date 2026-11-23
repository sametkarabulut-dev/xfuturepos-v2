---
tip: fonksiyon
kod: "15.08.05-2"
arac: "[[Kullanım Ölçümü]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kullanım düşen planları göster

> Kod `15.08.05-2` · Araç: [[Kullanım Ölçümü]]

## Ne yapar
- Kullanım düşen planları göster
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
