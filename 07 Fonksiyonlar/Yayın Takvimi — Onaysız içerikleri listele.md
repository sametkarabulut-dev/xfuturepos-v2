---
tip: fonksiyon
kod: "15.03.01-2"
arac: "[[Yayın Takvimi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Onaysız içerikleri listele

> Kod `15.03.01-2` · Araç: [[Yayın Takvimi]]

## Ne yapar
- Onaysız içerikleri listele
- Bağlı modül: Kanal bazlı içerik takvimi ve boş slot.

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
