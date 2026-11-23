---
tip: fonksiyon
kod: "13.06.03-1"
arac: "[[Hakediş Kesinti]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# ABC hakedişini kesintili hesapla

> Kod `13.06.03-1` · Araç: [[Hakediş Kesinti]]

## Ne yapar
- ABC hakedişini kesintili hesapla
- Bağlı modül: Fire/eksik/ret kesintili fasoncu ödemesi. Çekirdek genişleme: Muhasebe & Gelir-Gider.

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
