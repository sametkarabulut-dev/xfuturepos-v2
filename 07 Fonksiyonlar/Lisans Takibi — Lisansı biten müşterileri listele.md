---
tip: fonksiyon
kod: "15.07.04-1"
arac: "[[Lisans Takibi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Lisansı biten müşterileri listele

> Kod `15.07.04-1` · Araç: [[Lisans Takibi]]

## Ne yapar
- Lisansı biten müşterileri listele
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
