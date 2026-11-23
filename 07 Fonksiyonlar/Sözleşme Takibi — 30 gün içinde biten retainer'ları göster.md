---
tip: fonksiyon
kod: "15.00.05-1"
arac: "[[Sözleşme Takibi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# 30 gün içinde biten retainer'ları göster

> Kod `15.00.05-1` · Araç: [[Sözleşme Takibi]]

## Ne yapar
- 30 gün içinde biten retainer'ları göster
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
