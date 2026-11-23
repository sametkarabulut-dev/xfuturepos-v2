---
tip: fonksiyon
kod: "16.04.03-1"
arac: "[[Hasılat izin]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Ön satış kaç?

> Kod `16.04.03-1` · Araç: [[Hasılat izin]]

## Ne yapar
- Ön satış kaç?
- Bağlı modül: Bilet/hasılat özeti ve izin/güvenlik kalemleri.

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
