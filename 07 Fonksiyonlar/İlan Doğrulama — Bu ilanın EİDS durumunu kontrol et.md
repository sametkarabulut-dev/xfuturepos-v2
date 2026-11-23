---
tip: fonksiyon
kod: "09.00.03-1"
arac: "[[İlan Doğrulama]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu ilanın EİDS durumunu kontrol et

> Kod `09.00.03-1` · Araç: [[İlan Doğrulama]]

## Ne yapar
- Bu ilanın EİDS durumunu kontrol et
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
