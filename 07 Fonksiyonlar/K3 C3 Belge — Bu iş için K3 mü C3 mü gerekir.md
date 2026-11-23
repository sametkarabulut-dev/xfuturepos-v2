---
tip: fonksiyon
kod: "12.05.04-1"
arac: "[[K3 C3 Belge]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu iş için K3 mü C3 mü gerekir

> Kod `12.05.04-1` · Araç: [[K3 C3 Belge]]

## Ne yapar
- Bu iş için K3 mü C3 mü gerekir
- Bağlı modül: İşin yurt içi/uluslararası olmasına göre K3 veya C3 yönlendirmesi.

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
