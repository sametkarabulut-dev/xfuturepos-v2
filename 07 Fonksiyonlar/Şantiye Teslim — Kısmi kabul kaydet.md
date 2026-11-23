---
tip: fonksiyon
kod: "10.05.03-2"
arac: "[[Şantiye Teslim]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kısmi kabul kaydet

> Kod `10.05.03-2` · Araç: [[Şantiye Teslim]]

## Ne yapar
- Kısmi kabul kaydet
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
