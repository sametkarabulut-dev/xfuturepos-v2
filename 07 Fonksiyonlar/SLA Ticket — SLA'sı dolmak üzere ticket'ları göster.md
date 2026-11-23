---
tip: fonksiyon
kod: "15.07.01-1"
arac: "[[SLA Ticket]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# SLA'sı dolmak üzere ticket'ları göster

> Kod `15.07.01-1` · Araç: [[SLA Ticket]]

## Ne yapar
- SLA'sı dolmak üzere ticket'ları göster
- Bağlı modül: Talep kuyruğu, SLA süre ve öncelik.

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
