---
tip: fonksiyon
kod: "12.07.01-2"
arac: "[[Lokasyon Stok]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Sayım farkı olan gözleri listele

> Kod `12.07.01-2` · Araç: [[Lokasyon Stok]]

## Ne yapar
- Sayım farkı olan gözleri listele
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
