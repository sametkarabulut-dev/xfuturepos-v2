---
tip: fonksiyon
kod: "12.05.03-2"
arac: "[[Ekip Atama]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Paketleme malzemesi eksiği var mı

> Kod `12.05.03-2` · Araç: [[Ekip Atama]]

## Ne yapar
- Paketleme malzemesi eksiği var mı
- Bağlı modül: Taşınma günü kamyon, ekip ve paketleme malzemesi ataması.

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
