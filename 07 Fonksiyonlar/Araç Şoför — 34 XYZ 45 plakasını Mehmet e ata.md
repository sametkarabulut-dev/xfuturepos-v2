---
tip: fonksiyon
kod: "12.00.05-2"
arac: "[[Araç Şoför]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# 34 XYZ 45 plakasını Mehmet e ata

> Kod `12.00.05-2` · Araç: [[Araç Şoför]]

## Ne yapar
- 34 XYZ 45 plakasını Mehmet e ata
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
