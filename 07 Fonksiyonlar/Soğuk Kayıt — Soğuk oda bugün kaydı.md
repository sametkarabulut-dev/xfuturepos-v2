---
tip: fonksiyon
kod: "13.05.04-1"
arac: "[[Soğuk Kayıt]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Soğuk oda bugün kaydı

> Kod `13.05.04-1` · Araç: [[Soğuk Kayıt]]

## Ne yapar
- Soğuk oda bugün kaydı
- Bağlı modül: Basit sıcaklık/ölçüm günlüğü

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
