---
tip: fonksiyon
kod: "15.07.05-2"
arac: "[[Uzaktan Bağlantı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Oturum notunu özetle

> Kod `15.07.05-2` · Araç: [[Uzaktan Bağlantı]]

## Ne yapar
- Oturum notunu özetle
- Bağlı modül: Uzaktan erişim kaydı ve oturum notu.

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
