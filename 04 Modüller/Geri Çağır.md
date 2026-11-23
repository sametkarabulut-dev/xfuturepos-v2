---
tip: modul
kod: "13.05.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Geri Çağır

> Kod `13.05.05` · [[13 Üretim & İmalat]]

## Ne yapar
- Lot bazlı geri çağırma ve müşteri listesi. Çekirdek genişleme: CRM.

## Özellikler
### MVP
- Lot G-90 geri çağır
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Etkilenen fatura/irsaliye listesi

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- CRM, e-İrsaliye

## Mevzuat
- 5996 izlenebilirlik

## Yeniden kullanım
- **Araç türü:** ozel
- **[[13 Üretim & İmalat]]:** sektör/alt araç

## Kullanan işletme türleri
```base
filters:
  and:
    - 'tip == "isletme"'
    - file.hasLink(this.file)
views:
  - type: table
    name: Kullanan işletme türleri
```
