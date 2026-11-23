---
tip: fonksiyon
kod: "13.01.01-1"
arac: "[[Sipariş Emri]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Sipariş 120'yi iş emrine çevir

> Kod `13.01.01-1` · Araç: [[Sipariş Emri]]

## Ne yapar
- Sipariş 120'yi iş emrine çevir
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
