---
tip: fonksiyon
kod: "13.00.05-2"
arac: "[[Fason Mutabakat]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Fire aşımını hakedişten kes

> Kod `13.00.05-2` · Araç: [[Fason Mutabakat]]

## Ne yapar
- Fire aşımını hakedişten kes
- Bağlı modül: Sevk, dönüş, kalite, fire, hakediş ve fatura eşleştirme zinciri. Çekirdek genişleme: Muhasebe & Gelir-Gider.

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
