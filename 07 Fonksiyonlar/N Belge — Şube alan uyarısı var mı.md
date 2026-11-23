---
tip: fonksiyon
kod: "12.03.05-2"
arac: "[[N Belge]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Şube alan uyarısı var mı

> Kod `12.03.05-2` · Araç: [[N Belge]]

## Ne yapar
- Şube alan uyarısı var mı
- Bağlı modül: N1/N2 süre ve şube alan uygunluk notu.

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
