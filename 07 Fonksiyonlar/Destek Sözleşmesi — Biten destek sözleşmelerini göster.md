---
tip: fonksiyon
kod: "15.07.03-1"
arac: "[[Destek Sözleşmesi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Biten destek sözleşmelerini göster

> Kod `15.07.03-1` · Araç: [[Destek Sözleşmesi]]

## Ne yapar
- Biten destek sözleşmelerini göster
- Bağlı modül: Bakım sözleşmesi süresi ve yenileme.

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
