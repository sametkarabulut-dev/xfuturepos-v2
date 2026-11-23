---
tip: fonksiyon
kod: "13.01.01-2"
arac: "[[Sipariş Emri]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bugün teslimler

> Kod `13.01.01-2` · Araç: [[Sipariş Emri]]

## Ne yapar
- Bugün teslimler
- Bağlı modül: Satış siparişinden iş emri ve termin kilidi. Çekirdek genişleme: CRM.

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
