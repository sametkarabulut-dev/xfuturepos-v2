---
tip: fonksiyon
kod: "15.06.04-2"
arac: "[[Yayın İlan Eşleme]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Çakışan slotları listele

> Kod `15.06.04-2` · Araç: [[Yayın İlan Eşleme]]

## Ne yapar
- Çakışan slotları listele
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
