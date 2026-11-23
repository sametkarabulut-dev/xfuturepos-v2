---
tip: fonksiyon
kod: "10.00.03-2"
arac: "[[Metraj Hakediş]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kalıp m² farkını göster

> Kod `10.00.03-2` · Araç: [[Metraj Hakediş]]

## Ne yapar
- Kalıp m² farkını göster
- Bağlı modül: Poz/metraj hakediş ve kesintiler; Muhasebe genişlemesi.

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
