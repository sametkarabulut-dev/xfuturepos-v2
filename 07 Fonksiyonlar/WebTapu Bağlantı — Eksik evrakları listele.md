---
tip: fonksiyon
kod: "09.04.05-2"
arac: "[[WebTapu Bağlantı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Eksik evrakları listele

> Kod `09.04.05-2` · Araç: [[WebTapu Bağlantı]]

## Ne yapar
- Eksik evrakları listele
- Bağlı modül: Değerleme uzmanı WebTapu başvuru/belge durumunun dosya bazlı takibi.

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
