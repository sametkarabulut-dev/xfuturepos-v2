---
tip: fonksiyon
kod: "16.00.05-2"
arac: "[[Kişi sayısı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Son kişi güncellemesi?

> Kod `16.00.05-2` · Araç: [[Kişi sayısı]]

## Ne yapar
- Son kişi güncellemesi?
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
