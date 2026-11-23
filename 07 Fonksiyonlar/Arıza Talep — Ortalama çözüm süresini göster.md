---
tip: fonksiyon
kod: "09.03.03-2"
arac: "[[Arıza Talep]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Ortalama çözüm süresini göster

> Kod `09.03.03-2` · Araç: [[Arıza Talep]]

## Ne yapar
- Ortalama çözüm süresini göster
- Bağlı modül: Kat maliki/kiracı talep, teknisyen atama ve SLA.

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
