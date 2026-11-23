---
tip: fonksiyon
kod: "12.04.04-1"
arac: "[[P Belge]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# P1 taşıt sayısı eksiği var mı

> Kod `12.04.04-1` · Araç: [[P Belge]]

## Ne yapar
- P1 taşıt sayısı eksiği var mı
- Bağlı modül: P1/P2 geçerlilik ve özmal taşıt sayısı kontrolü.

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
