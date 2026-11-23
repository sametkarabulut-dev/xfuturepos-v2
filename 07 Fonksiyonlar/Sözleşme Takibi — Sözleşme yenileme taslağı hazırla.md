---
tip: fonksiyon
kod: "15.00.05-2"
arac: "[[Sözleşme Takibi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Sözleşme yenileme taslağı hazırla

> Kod `15.00.05-2` · Araç: [[Sözleşme Takibi]]

## Ne yapar
- Sözleşme yenileme taslağı hazırla
- Bağlı modül: Proje ve retainer bitiş tarihleri; yenileme hatırlatması (ürün aboneliği 15.08'de).

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
