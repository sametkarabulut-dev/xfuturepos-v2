---
tip: fonksiyon
kod: "12.05.01-2"
arac: "[[Keşif Randevu (Lojistik)]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu keşfi tamamlandı yap

> Kod `12.05.01-2` · Araç: [[Keşif Randevu (Lojistik)]]

## Ne yapar
- Bu keşfi tamamlandı yap
- Bağlı modül: Keşif günü, kat, asansör, m²; teklife girdi. CRM çekirdeğine iş akışı bağlar.

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
