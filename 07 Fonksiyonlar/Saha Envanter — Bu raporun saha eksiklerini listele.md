---
tip: fonksiyon
kod: "09.04.03-1"
arac: "[[Saha Envanter]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu raporun saha eksiklerini listele

> Kod `09.04.03-1` · Araç: [[Saha Envanter]]

## Ne yapar
- Bu raporun saha eksiklerini listele
- Bağlı modül: Yerinde tespit formu, foto, ölçü ve karşılaştırılabilir örnek kayıtları.

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
