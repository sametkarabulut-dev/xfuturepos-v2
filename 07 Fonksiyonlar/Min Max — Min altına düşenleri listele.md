---
tip: fonksiyon
kod: "13.02.03-1"
arac: "[[Min Max]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Min altına düşenleri listele

> Kod `13.02.03-1` · Araç: [[Min Max]]

## Ne yapar
- Min altına düşenleri listele
- Bağlı modül: Yeniden üretim tetik noktası

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
