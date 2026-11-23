---
tip: fonksiyon
kod: "15.07.01-2"
arac: "[[SLA Ticket]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Eksik bilgili talepleri ayıkla

> Kod `15.07.01-2` · Araç: [[SLA Ticket]]

## Ne yapar
- Eksik bilgili talepleri ayıkla
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
