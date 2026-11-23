---
tip: fonksiyon
kod: "12.07.01-1"
arac: "[[Lokasyon Stok]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# X markanın stokunu göster

> Kod `12.07.01-1` · Araç: [[Lokasyon Stok]]

## Ne yapar
- X markanın stokunu göster
- Bağlı modül: Mal sahibi, SKU ve göz/adres bazlı stok; kabul ve sayım.

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
