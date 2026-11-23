---
tip: fonksiyon
kod: "12.00.04-2"
arac: "[[Teslim Kanıtı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Dün reddedilen teslimleri listele

> Kod `12.00.04-2` · Araç: [[Teslim Kanıtı]]

## Ne yapar
- Dün reddedilen teslimleri listele
- Bağlı modül: Alıcı imza/foto/red ve hasar notu; faturalama için çekirdek e-Fatura sürecine veri bırakır.

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
