---
tip: fonksiyon
kod: "15.06.04-1"
arac: "[[Yayın İlan Eşleme]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yayına denk gelmeyen ilanları bul

> Kod `15.06.04-1` · Araç: [[Yayın İlan Eşleme]]

## Ne yapar
- Yayına denk gelmeyen ilanları bul
- Bağlı modül: Satılmış ilanın yayın slotuna denk gelmesi.

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
