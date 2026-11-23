---
tip: fonksiyon
kod: "09.00.07-2"
arac: "[[Komisyon Hesabı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Danışman payını göster

> Kod `09.00.07-2` · Araç: [[Komisyon Hesabı]]

## Ne yapar
- Danışman payını göster
- Bağlı modül: Muhasebe & Gelir-Gider genişlemesi: işlem komisyonu ve ofis/danışman payı önerisi.

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
