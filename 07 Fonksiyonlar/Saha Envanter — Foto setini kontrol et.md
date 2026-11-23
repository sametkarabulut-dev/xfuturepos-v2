---
tip: fonksiyon
kod: "09.04.03-2"
arac: "[[Saha Envanter]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Foto setini kontrol et

> Kod `09.04.03-2` · Araç: [[Saha Envanter]]

## Ne yapar
- Foto setini kontrol et
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
