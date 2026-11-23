---
tip: fonksiyon
kod: "15.03.01-1"
arac: "[[Yayın Takvimi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu hafta boş kalan günleri göster

> Kod `15.03.01-1` · Araç: [[Yayın Takvimi]]

## Ne yapar
- Bu hafta boş kalan günleri göster
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
