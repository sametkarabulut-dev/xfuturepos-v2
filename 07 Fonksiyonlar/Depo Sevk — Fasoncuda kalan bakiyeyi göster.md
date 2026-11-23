---
tip: fonksiyon
kod: "13.00.04-2"
arac: "[[Depo Sevk]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Fasoncuda kalan bakiyeyi göster

> Kod `13.00.04-2` · Araç: [[Depo Sevk]]

## Ne yapar
- Fasoncuda kalan bakiyeyi göster
- Bağlı modül: İş emrine bağlı malzeme çıkış/iade ve fason depo bakiyesi. Çekirdek genişleme: e-Fatura/e-Arşiv (e-irsaliye köprüsü).

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
