---
tip: fonksiyon
kod: "15.01.02-2"
arac: "[[Kabul Kontrolü]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# UAT notlarını maddele

> Kod `15.01.02-2` · Araç: [[Kabul Kontrolü]]

## Ne yapar
- UAT notlarını maddele
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
