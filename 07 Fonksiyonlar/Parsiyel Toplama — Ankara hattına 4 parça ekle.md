---
tip: fonksiyon
kod: "12.03.01-1"
arac: "[[Parsiyel Toplama]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Ankara hattına 4 parça ekle

> Kod `12.03.01-1` · Araç: [[Parsiyel Toplama]]

## Ne yapar
- Ankara hattına 4 parça ekle
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
