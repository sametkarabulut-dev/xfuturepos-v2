---
tip: fonksiyon
kod: "15.01.02-1"
arac: "[[Kabul Kontrolü]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Kabul için eksikleri çıkar

> Kod `15.01.02-1` · Araç: [[Kabul Kontrolü]]

## Ne yapar
- Kabul için eksikleri çıkar
- Bağlı modül: Kabul kriteri, UAT ve imza öncesi eksikler.

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
