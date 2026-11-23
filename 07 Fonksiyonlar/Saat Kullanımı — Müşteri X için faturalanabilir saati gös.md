---
tip: fonksiyon
kod: "15.00.02-2"
arac: "[[Saat Kullanımı]]"
kapsam: sektorel
kullanim: 1
durum: tamamlandi
---
# Müşteri X için faturalanabilir saati göster

> Kod `15.00.02-2` · Araç: [[Saat Kullanımı]]

## Ne yapar
- Müşteri X için faturalanabilir saati göster
- Bağlı modül: Faturalanabilir ve faturalanamayan saat kaydı; proje veya retainer ile eşleme.

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
