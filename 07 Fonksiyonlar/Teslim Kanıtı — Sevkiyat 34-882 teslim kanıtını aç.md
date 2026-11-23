---
tip: fonksiyon
kod: "12.00.04-1"
arac: "[[Teslim Kanıtı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Sevkiyat 34-882 teslim kanıtını aç

> Kod `12.00.04-1` · Araç: [[Teslim Kanıtı]]

## Ne yapar
- Sevkiyat 34-882 teslim kanıtını aç
- Bağlı modül: Alıcı imza/foto/red ve hasar notu; faturalama için çekirdek e-Fatura sürecine veri bırakır.

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
