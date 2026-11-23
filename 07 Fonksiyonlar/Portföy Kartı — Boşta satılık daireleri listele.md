---
tip: fonksiyon
kod: "09.00.01-1"
arac: "[[Portföy Kartı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Boşta satılık daireleri listele

> Kod `09.00.01-1` · Araç: [[Portföy Kartı]]

## Ne yapar
- Boşta satılık daireleri listele
- Bağlı modül: Satış/kira/işletme için taşınmaz kimliği, özellikler, durum ve medya yönetimi.

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
