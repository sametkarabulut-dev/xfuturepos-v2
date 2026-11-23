---
tip: fonksiyon
kod: "10.01.03-1"
arac: "[[Maliyet Bütçe]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu ay bütçe sapmasını göster

> Kod `10.01.03-1` · Araç: [[Maliyet Bütçe]]

## Ne yapar
- Bu ay bütçe sapmasını göster
- Bağlı modül: Keşif vs gerçekleşen. Çekirdek genişleme: Muhasebe.

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
