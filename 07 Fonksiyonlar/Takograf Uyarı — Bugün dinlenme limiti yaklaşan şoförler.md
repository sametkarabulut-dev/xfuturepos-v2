---
tip: fonksiyon
kod: "12.01.04-1"
arac: "[[Takograf Uyarı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bugün dinlenme limiti yaklaşan şoförler

> Kod `12.01.04-1` · Araç: [[Takograf Uyarı]]

## Ne yapar
- Bugün dinlenme limiti yaklaşan şoförler
- Bağlı modül: Planlanan sürüşe göre dinlenme/süre aşımı hatırlatması; cihaz API’si bağlanmadan çalışır.

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
