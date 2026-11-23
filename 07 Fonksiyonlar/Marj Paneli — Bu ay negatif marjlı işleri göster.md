---
tip: fonksiyon
kod: "12.06.05-1"
arac: "[[Marj Paneli]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu ay negatif marjlı işleri göster

> Kod `12.06.05-1` · Araç: [[Marj Paneli]]

## Ne yapar
- Bu ay negatif marjlı işleri göster
- Bağlı modül: Alış navlun ile satış navlun farkı; zararlı iş uyarısı.

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
