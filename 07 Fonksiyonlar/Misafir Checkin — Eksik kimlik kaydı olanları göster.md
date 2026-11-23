---
tip: fonksiyon
kod: "09.05.03-2"
arac: "[[Misafir Checkin]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Eksik kimlik kaydı olanları göster

> Kod `09.05.03-2` · Araç: [[Misafir Checkin]]

## Ne yapar
- Eksik kimlik kaydı olanları göster
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
