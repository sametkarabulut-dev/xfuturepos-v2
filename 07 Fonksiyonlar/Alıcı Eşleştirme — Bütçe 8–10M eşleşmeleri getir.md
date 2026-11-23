---
tip: fonksiyon
kod: "09.01.01-2"
arac: "[[Alıcı Eşleştirme]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bütçe 8–10M eşleşmeleri getir

> Kod `09.01.01-2` · Araç: [[Alıcı Eşleştirme]]

## Ne yapar
- Bütçe 8–10M eşleşmeleri getir
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
