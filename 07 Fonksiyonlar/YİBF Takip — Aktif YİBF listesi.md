---
tip: fonksiyon
kod: "10.07.01-1"
arac: "[[YİBF Takip]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Aktif YİBF listesi

> Kod `10.07.01-1` · Araç: [[YİBF Takip]]

## Ne yapar
- Aktif YİBF listesi
- Bağlı modül: YİBF ve atama takibi.

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
