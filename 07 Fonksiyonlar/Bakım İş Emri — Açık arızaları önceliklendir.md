---
tip: fonksiyon
kod: "09.02.03-1"
arac: "[[Bakım İş Emri]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Açık arızaları önceliklendir

> Kod `09.02.03-1` · Araç: [[Bakım İş Emri]]

## Ne yapar
- Açık arızaları önceliklendir
- Bağlı modül: Kiracı/malik arıza kaydı, tedarikçi atama ve kapanış.

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
