---
tip: fonksiyon
kod: "12.05.05-1"
arac: "[[Sigorta Teklif]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bu taşınma için sigorta tutarı öner

> Kod `12.05.05-1` · Araç: [[Sigorta Teklif]]

## Ne yapar
- Bu taşınma için sigorta tutarı öner
- Bağlı modül: Beyan değerine göre nakliyat sigortası maddesini teklife ekleme hatırlatması.

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
