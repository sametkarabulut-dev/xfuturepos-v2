---
tip: fonksiyon
kod: "12.00.03-1"
arac: "[[U-ETDS Köprüsü]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# 34 ABC 123 seferini U-ETDS için hazırla

> Kod `12.00.03-1` · Araç: [[U-ETDS Köprüsü]]

## Ne yapar
- 34 ABC 123 seferini U-ETDS için hazırla
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
