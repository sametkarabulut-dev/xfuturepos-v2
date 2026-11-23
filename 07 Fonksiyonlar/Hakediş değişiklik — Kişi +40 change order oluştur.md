---
tip: fonksiyon
kod: "16.03.03-1"
arac: "[[Hakediş değişiklik]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kişi +40 change order oluştur

> Kod `16.03.03-1` · Araç: [[Hakediş değişiklik]]

## Ne yapar
- Kişi +40 change order oluştur
- Bağlı modül: Change order ve faturalanabilir fark.

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
