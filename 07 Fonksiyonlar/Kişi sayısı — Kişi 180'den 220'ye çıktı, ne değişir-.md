---
tip: fonksiyon
kod: "16.00.05-1"
arac: "[[Kişi sayısı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kişi 180'den 220'ye çıktı, ne değişir?

> Kod `16.00.05-1` · Araç: [[Kişi sayısı]]

## Ne yapar
- Kişi 180'den 220'ye çıktı, ne değişir?
- Bağlı modül: Sözleşme kişi sayısı ile güncel sayıyı ve etkileri takip eder.

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
