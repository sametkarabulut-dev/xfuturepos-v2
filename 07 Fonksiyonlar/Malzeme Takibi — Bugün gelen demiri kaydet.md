---
tip: fonksiyon
kod: "10.00.05-1"
arac: "[[Malzeme Takibi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bugün gelen demiri kaydet

> Kod `10.00.05-1` · Araç: [[Malzeme Takibi]]

## Ne yapar
- Bugün gelen demiri kaydet
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
