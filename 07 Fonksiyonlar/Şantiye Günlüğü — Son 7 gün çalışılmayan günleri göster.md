---
tip: fonksiyon
kod: "10.00.04-2"
arac: "[[Şantiye Günlüğü]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Son 7 gün çalışılmayan günleri göster

> Kod `10.00.04-2` · Araç: [[Şantiye Günlüğü]]

## Ne yapar
- Son 7 gün çalışılmayan günleri göster
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
