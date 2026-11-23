---
tip: fonksiyon
kod: "16.00.01-1"
arac: "[[Etkinlik takvimi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# 15 Haziran akşam boş mu?

> Kod `16.00.01-1` · Araç: [[Etkinlik takvimi]]

## Ne yapar
- 15 Haziran akşam boş mu?
- Bağlı modül: Tarih/seans/kaynak doluluğu; opsiyon ve kesin kayıt; çakışma engeli.

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
