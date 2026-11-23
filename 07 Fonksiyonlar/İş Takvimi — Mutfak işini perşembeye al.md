---
tip: fonksiyon
kod: "10.04.03-1"
arac: "[[İş Takvimi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Mutfak işini perşembeye al

> Kod `10.04.03-1` · Araç: [[İş Takvimi]]

## Ne yapar
- Mutfak işini perşembeye al
- Bağlı modül: Usta ve malzeme günleri.

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
