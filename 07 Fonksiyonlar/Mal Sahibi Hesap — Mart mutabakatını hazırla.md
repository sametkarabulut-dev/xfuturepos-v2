---
tip: fonksiyon
kod: "12.07.03-1"
arac: "[[Mal Sahibi Hesap]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Mart mutabakatını hazırla

> Kod `12.07.03-1` · Araç: [[Mal Sahibi Hesap]]

## Ne yapar
- Mart mutabakatını hazırla
- Bağlı modül: Depolama ve işlem ücretleri; dönem mutabakatı çekirdek e-Faturaya el verir.

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
