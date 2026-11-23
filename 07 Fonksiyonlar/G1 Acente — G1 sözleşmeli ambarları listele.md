---
tip: fonksiyon
kod: "12.03.04-1"
arac: "[[G1 Acente]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# G1 sözleşmeli ambarları listele

> Kod `12.03.04-1` · Araç: [[G1 Acente]]

## Ne yapar
- G1 sözleşmeli ambarları listele
- Bağlı modül: Başka N belgesi adına yük kabul eden G1 acente sözleşmeleri.

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
