---
tip: fonksiyon
kod: "13.03.03-2"
arac: "[[Dönüş İrsaliye]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# İrsaliye hazırla

> Kod `13.03.03-2` · Araç: [[Dönüş İrsaliye]]

## Ne yapar
- İrsaliye hazırla
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
