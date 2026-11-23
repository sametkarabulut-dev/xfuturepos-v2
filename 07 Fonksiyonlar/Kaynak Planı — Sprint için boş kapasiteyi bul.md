---
tip: fonksiyon
kod: "15.00.06-2"
arac: "[[Kaynak Planı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Sprint için boş kapasiteyi bul

> Kod `15.00.06-2` · Araç: [[Kaynak Planı]]

## Ne yapar
- Sprint için boş kapasiteyi bul
- Bağlı modül: Kişi-hafta kapasite ve aşırı yük görünümü.

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
