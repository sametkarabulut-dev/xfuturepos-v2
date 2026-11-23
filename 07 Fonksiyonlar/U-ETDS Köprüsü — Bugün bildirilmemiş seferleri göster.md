---
tip: fonksiyon
kod: "12.00.03-2"
arac: "[[U-ETDS Köprüsü]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Bugün bildirilmemiş seferleri göster

> Kod `12.00.03-2` · Araç: [[U-ETDS Köprüsü]]

## Ne yapar
- Bugün bildirilmemiş seferleri göster
- Bağlı modül: Sefer, yük, şoför bildirimi için SOAP alanlarını doldurur; gönderim onaylıdır. K1/K3/C3/L1/L2/N1/N2 (TM’de C1/K2) için.

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
