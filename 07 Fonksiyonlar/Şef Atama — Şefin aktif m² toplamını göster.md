---
tip: fonksiyon
kod: "10.01.04-2"
arac: "[[Şef Atama]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Şefin aktif m² toplamını göster

> Kod `10.01.04-2` · Araç: [[Şef Atama]]

## Ne yapar
- Şefin aktif m² toplamını göster
- Bağlı modül: Şantiye şefi atama ve limit.

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
