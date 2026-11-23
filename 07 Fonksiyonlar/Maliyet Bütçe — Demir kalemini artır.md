---
tip: fonksiyon
kod: "10.01.03-2"
arac: "[[Maliyet Bütçe]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Demir kalemini artır

> Kod `10.01.03-2` · Araç: [[Maliyet Bütçe]]

## Ne yapar
- Demir kalemini artır
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
