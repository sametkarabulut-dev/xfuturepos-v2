---
tip: fonksiyon
kod: "12.03.03-2"
arac: "[[Ambar Stok]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# 3 gündür bekleyen parçalar

> Kod `12.03.03-2` · Araç: [[Ambar Stok]]

## Ne yapar
- 3 gündür bekleyen parçalar
- Bağlı modül: Kapalı ambar giriş-çıkış, göz/yer ve bekleyen parça arama.

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
