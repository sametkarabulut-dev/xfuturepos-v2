---
tip: fonksiyon
kod: "13.01.03-1"
arac: "[[Termin Alarm]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Geç kalacak işleri söyle

> Kod `13.01.03-1` · Araç: [[Termin Alarm]]

## Ne yapar
- Geç kalacak işleri söyle
- Bağlı modül: Teslim riski ve dar boğaz uyarısı. Çekirdek genişleme: CRM.

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
