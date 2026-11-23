---
tip: fonksiyon
kod: "12.00.01-1"
arac: "[[Sevkiyat Kartı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bugün yüklenen 3 sevkiyatı listele

> Kod `12.00.01-1` · Araç: [[Sevkiyat Kartı]]

## Ne yapar
- Bugün yüklenen 3 sevkiyatı listele
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
