---
tip: fonksiyon
kod: "12.03.01-2"
arac: "[[Parsiyel Toplama]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bugün kabul edilen parçaları listele

> Kod `12.03.01-2` · Araç: [[Parsiyel Toplama]]

## Ne yapar
- Bugün kabul edilen parçaları listele
- Bağlı modül: Parça yük kabul, etiketleme ve hat aracına konsolidasyon.

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
