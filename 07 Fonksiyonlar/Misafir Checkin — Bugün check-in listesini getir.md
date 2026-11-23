---
tip: fonksiyon
kod: "09.05.03-1"
arac: "[[Misafir Checkin]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bugün check-in listesini getir

> Kod `09.05.03-1` · Araç: [[Misafir Checkin]]

## Ne yapar
- Bugün check-in listesini getir
- Bağlı modül: Kimlik/pasaport kaydı, giriş-çıkış ve ev kuralları onayı.

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
