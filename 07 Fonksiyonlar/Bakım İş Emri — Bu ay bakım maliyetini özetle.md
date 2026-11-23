---
tip: fonksiyon
kod: "09.02.03-2"
arac: "[[Bakım İş Emri]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu ay bakım maliyetini özetle

> Kod `09.02.03-2` · Araç: [[Bakım İş Emri]]

## Ne yapar
- Bu ay bakım maliyetini özetle
- Bağlı modül: Kiracı/malik arıza kaydı, tedarikçi atama ve kapanış.

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
