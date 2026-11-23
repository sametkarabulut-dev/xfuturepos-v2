---
tip: fonksiyon
kod: "09.00.07-1"
arac: "[[Komisyon Hesabı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu satışta komisyon tutarını hesapla

> Kod `09.00.07-1` · Araç: [[Komisyon Hesabı]]

## Ne yapar
- Bu satışta komisyon tutarını hesapla
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
