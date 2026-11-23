---
tip: fonksiyon
kod: "09.00.05-2"
arac: "[[Sözleşme Taslağı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kira sözleşmesi madde özetini çıkar

> Kod `09.00.05-2` · Araç: [[Sözleşme Taslağı]]

## Ne yapar
- Kira sözleşmesi madde özetini çıkar
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
