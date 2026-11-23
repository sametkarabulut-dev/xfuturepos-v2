---
tip: fonksiyon
kod: "12.00.05-1"
arac: "[[Araç Şoför]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# SRC si 30 günde bitecek şoförleri göster

> Kod `12.00.05-1` · Araç: [[Araç Şoför]]

## Ne yapar
- SRC si 30 günde bitecek şoförleri göster
- Bağlı modül: Plaka, taşıt kartı, SRC/psikoteknik bitiş ve şoför-araç eşlemesi. Personel çekirdeğinin filo genişlemesi.

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
