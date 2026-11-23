---
tip: fonksiyon
kod: "09.00.03-2"
arac: "[[İlan Doğrulama]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yetkisiz ilanları işaretle

> Kod `09.00.03-2` · Araç: [[İlan Doğrulama]]

## Ne yapar
- Yetkisiz ilanları işaretle
- Bağlı modül: İlan öncesi kimlik/yetki doğrulama durumu ve yayın checklist'i; EİDS uyumu.

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
