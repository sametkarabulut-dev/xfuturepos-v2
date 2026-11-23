---
tip: fonksiyon
kod: "10.02.01-2"
arac: "[[İş Emri]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# C blok sıva emrini tamamla

> Kod `10.02.01-2` · Araç: [[İş Emri]]

## Ne yapar
- C blok sıva emrini tamamla
- Bağlı modül: Mahal/poz iş emri.

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
