---
tip: fonksiyon
kod: "09.01.01-1"
arac: "[[Alıcı Eşleştirme]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu alıcıya 5 aday öner

> Kod `09.01.01-1` · Araç: [[Alıcı Eşleştirme]]

## Ne yapar
- Bu alıcıya 5 aday öner
- Bağlı modül: CRM genişlemesi: bütçe/lokasyon/özellik ile portföy adayı skorlama.

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
