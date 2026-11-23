---
tip: fonksiyon
kod: "16.03.03-2"
arac: "[[Hakediş değişiklik]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu ay kesilecek hakediş?

> Kod `16.03.03-2` · Araç: [[Hakediş değişiklik]]

## Ne yapar
- Bu ay kesilecek hakediş?
- Bağlı modül: Change order ve faturalanabilir fark.

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
