---
tip: fonksiyon
kod: "13.03.03-1"
arac: "[[Dönüş İrsaliye]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Mamulü müşteriye sevk et

> Kod `13.03.03-1` · Araç: [[Dönüş İrsaliye]]

## Ne yapar
- Mamulü müşteriye sevk et
- Bağlı modül: Mamulün müşteriye sevki. Çekirdek genişleme: e-Fatura/e-Arşiv.

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
