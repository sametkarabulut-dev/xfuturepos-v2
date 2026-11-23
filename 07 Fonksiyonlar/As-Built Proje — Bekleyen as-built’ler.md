---
tip: fonksiyon
kod: "10.03.04-2"
arac: "[[As-Built Proje]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bekleyen as-built’ler

> Kod `10.03.04-2` · Araç: [[As-Built Proje]]

## Ne yapar
- Bekleyen as-built’ler
- Bağlı modül: Uygulama sonrası çizim teslimi.

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
