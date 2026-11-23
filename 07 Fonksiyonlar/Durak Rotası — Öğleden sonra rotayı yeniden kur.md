---
tip: fonksiyon
kod: "12.04.01-2"
arac: "[[Durak Rotası]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Öğleden sonra rotayı yeniden kur

> Kod `12.04.01-2` · Araç: [[Durak Rotası]]

## Ne yapar
- Öğleden sonra rotayı yeniden kur
- Bağlı modül: Çok duraklı teslim sırası; kurye gönderisi boyutu notu.

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
