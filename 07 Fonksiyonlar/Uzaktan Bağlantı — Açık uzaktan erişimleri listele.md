---
tip: fonksiyon
kod: "15.07.05-1"
arac: "[[Uzaktan Bağlantı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Açık uzaktan erişimleri listele

> Kod `15.07.05-1` · Araç: [[Uzaktan Bağlantı]]

## Ne yapar
- Açık uzaktan erişimleri listele
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
