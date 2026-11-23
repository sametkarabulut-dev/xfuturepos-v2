---
tip: fonksiyon
kod: "10.05.03-1"
arac: "[[Şantiye Teslim]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Reddedilen sevkiyatları göster

> Kod `10.05.03-1` · Araç: [[Şantiye Teslim]]

## Ne yapar
- Reddedilen sevkiyatları göster
- Bağlı modül: Kabul/red ve yanıt.

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
