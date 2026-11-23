---
tip: fonksiyon
kod: "15.00.06-1"
arac: "[[Kaynak Planı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kim aşırı yüklü?

> Kod `15.00.06-1` · Araç: [[Kaynak Planı]]

## Ne yapar
- Kim aşırı yüklü?
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
