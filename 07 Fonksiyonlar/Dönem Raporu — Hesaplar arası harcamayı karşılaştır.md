---
tip: fonksiyon
kod: "15.02.03-2"
arac: "[[Dönem Raporu]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Hesaplar arası harcamayı karşılaştır

> Kod `15.02.03-2` · Araç: [[Dönem Raporu]]

## Ne yapar
- Hesaplar arası harcamayı karşılaştır
- Bağlı modül: Dönem harcama, tıklama ve dönüşüm özeti.

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
