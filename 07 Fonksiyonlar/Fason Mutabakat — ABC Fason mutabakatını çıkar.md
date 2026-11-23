---
tip: fonksiyon
kod: "13.00.05-1"
arac: "[[Fason Mutabakat]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# ABC Fason mutabakatını çıkar

> Kod `13.00.05-1` · Araç: [[Fason Mutabakat]]

## Ne yapar
- ABC Fason mutabakatını çıkar
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
