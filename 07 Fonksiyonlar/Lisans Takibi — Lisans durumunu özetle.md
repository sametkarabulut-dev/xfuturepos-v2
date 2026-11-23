---
tip: fonksiyon
kod: "15.07.04-2"
arac: "[[Lisans Takibi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Lisans durumunu özetle

> Kod `15.07.04-2` · Araç: [[Lisans Takibi]]

## Ne yapar
- Lisans durumunu özetle
- Bağlı modül: Paket yazılım lisans ve iş ortaklığı kaydı.

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
