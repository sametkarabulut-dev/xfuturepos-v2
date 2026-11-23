---
tip: fonksiyon
kod: "10.00.04-1"
arac: "[[Şantiye Günlüğü]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bugünkü günlük raporu hazırla

> Kod `10.00.04-1` · Araç: [[Şantiye Günlüğü]]

## Ne yapar
- Bugünkü günlük raporu hazırla
- Bağlı modül: Operasyonel günlük; Şantiye-M hazırlık (otomatik API yok).

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
