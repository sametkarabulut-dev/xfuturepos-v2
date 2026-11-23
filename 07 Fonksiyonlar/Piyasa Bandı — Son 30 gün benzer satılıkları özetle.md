---
tip: fonksiyon
kod: "09.01.05-2"
arac: "[[Piyasa Bandı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Son 30 gün benzer satılıkları özetle

> Kod `09.01.05-2` · Araç: [[Piyasa Bandı]]

## Ne yapar
- Son 30 gün benzer satılıkları özetle
- Bağlı modül: Benzer ilanlardan bilgilendirme amaçlı fiyat bandı önerisi.

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
