---
tip: fonksiyon
kod: "09.05.02-2"
arac: "[[İzin Belgesi]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Denetim hatırlatmalarını göster

> Kod `09.05.02-2` · Araç: [[İzin Belgesi]]

## Ne yapar
- Denetim hatırlatmalarını göster
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
