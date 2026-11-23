---
tip: fonksiyon
kod: "09.05.05-1"
arac: "[[Kanal Yönetimi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kanallardaki fiyat farklarını göster

> Kod `09.05.05-1` · Araç: [[Kanal Yönetimi]]

## Ne yapar
- Kanallardaki fiyat farklarını göster
- Bağlı modül: OTA/ilan kanallarında takvim/fiyat senkron uyumsuzluk takibi.

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
