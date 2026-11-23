---
tip: fonksiyon
kod: "12.00.01-2"
arac: "[[Sevkiyat Kartı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# ABC Ltd sevkiyatını yolda yap

> Kod `12.00.01-2` · Araç: [[Sevkiyat Kartı]]

## Ne yapar
- ABC Ltd sevkiyatını yolda yap
- Bağlı modül: Yük/sevkiyat yaşam döngüsü: talep, yükleme, yolda, teslim; gönderici/alıcı, tonaj ve adres tek kartta.

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
