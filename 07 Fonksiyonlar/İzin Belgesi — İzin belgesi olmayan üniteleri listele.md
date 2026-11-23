---
tip: fonksiyon
kod: "09.05.02-1"
arac: "[[İzin Belgesi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# İzin belgesi olmayan üniteleri listele

> Kod `09.05.02-1` · Araç: [[İzin Belgesi]]

## Ne yapar
- İzin belgesi olmayan üniteleri listele
- Bağlı modül: e-Devlet izin belgesi numarası, yenileme ve iptal risk takibi.

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
