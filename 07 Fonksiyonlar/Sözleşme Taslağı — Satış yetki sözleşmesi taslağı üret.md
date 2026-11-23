---
tip: fonksiyon
kod: "09.00.05-1"
arac: "[[Sözleşme Taslağı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Satış yetki sözleşmesi taslağı üret

> Kod `09.00.05-1` · Araç: [[Sözleşme Taslağı]]

## Ne yapar
- Satış yetki sözleşmesi taslağı üret
- Bağlı modül: Satış/kira/yetkilendirme taslak üretimi; imza ve gönderim insan onayına bağlı.

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
