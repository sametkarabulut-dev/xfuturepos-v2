---
tip: fonksiyon
kod: "15.06.03-2"
arac: "[[Yasal Bilgi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# İletişim bilgisi güncelliğini kontrol et

> Kod `15.06.03-2` · Araç: [[Yasal Bilgi]]

## Ne yapar
- İletişim bilgisi güncelliğini kontrol et
- Bağlı modül: 5651 bilgilendirme ve iletişim bilgisi kontrolü.

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
