---
tip: fonksiyon
kod: "15.07.03-2"
arac: "[[Destek Sözleşmesi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Yenileme hatırlatması hazırla

> Kod `15.07.03-2` · Araç: [[Destek Sözleşmesi]]

## Ne yapar
- Yenileme hatırlatması hazırla
- Bağlı modül: Bakım sözleşmesi süresi ve yenileme.

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
