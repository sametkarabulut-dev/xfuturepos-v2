---
tip: fonksiyon
kod: "16.04.03-2"
arac: "[[Hasılat izin]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Özel güvenlik başvurusu yapıldı mı?

> Kod `16.04.03-2` · Araç: [[Hasılat izin]]

## Ne yapar
- Özel güvenlik başvurusu yapıldı mı?
- Bağlı modül: Bilet/hasılat özeti ve izin/güvenlik kalemleri.

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
