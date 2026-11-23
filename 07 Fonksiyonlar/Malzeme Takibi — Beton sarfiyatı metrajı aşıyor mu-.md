---
tip: fonksiyon
kod: "10.00.05-2"
arac: "[[Malzeme Takibi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Beton sarfiyatı metrajı aşıyor mu?

> Kod `10.00.05-2` · Araç: [[Malzeme Takibi]]

## Ne yapar
- Beton sarfiyatı metrajı aşıyor mu?
- Bağlı modül: İrsaliye kabul ve şantiye sarfiyatı. Çekirdek genişleme: e-Fatura.

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
