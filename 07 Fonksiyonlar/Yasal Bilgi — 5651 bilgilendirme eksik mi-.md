---
tip: fonksiyon
kod: "15.06.03-1"
arac: "[[Yasal Bilgi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# 5651 bilgilendirme eksik mi?

> Kod `15.06.03-1` · Araç: [[Yasal Bilgi]]

## Ne yapar
- 5651 bilgilendirme eksik mi?
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
