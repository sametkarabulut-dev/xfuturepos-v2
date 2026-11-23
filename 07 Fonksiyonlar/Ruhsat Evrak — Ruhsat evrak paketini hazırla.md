---
tip: fonksiyon
kod: "10.06.05-1"
arac: "[[Ruhsat Evrak]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Ruhsat evrak paketini hazırla

> Kod `10.06.05-1` · Araç: [[Ruhsat Evrak]]

## Ne yapar
- Ruhsat evrak paketini hazırla
- Bağlı modül: İdare evrak paketi.

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
