---
tip: fonksiyon
kod: "15.01.05-2"
arac: "[[Depo Bağlantısı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Açık PR'ları işlere eşle

> Kod `15.01.05-2` · Araç: [[Depo Bağlantısı]]

## Ne yapar
- Açık PR'ları işlere eşle
- Bağlı modül: Commit/PR kaydını iş kartına bağlama.

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
