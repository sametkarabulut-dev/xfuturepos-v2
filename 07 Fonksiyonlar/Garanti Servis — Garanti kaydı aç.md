---
tip: fonksiyon
kod: "10.04.05-1"
arac: "[[Garanti Servis]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Garanti kaydı aç

> Kod `10.04.05-1` · Araç: [[Garanti Servis]]

## Ne yapar
- Garanti kaydı aç
- Bağlı modül: Teslim sonrası servis.

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
