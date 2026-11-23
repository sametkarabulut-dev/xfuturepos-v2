---
tip: modul
kod: "13.03.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Müşteri Malzeme

> Kod `13.03.01` · [[13 Üretim & İmalat]]

## Ne yapar
- Müşteri emanet hammadde bakiyesi

## Özellikler
### MVP
- Müşteri Y kumaş bakiyesi
- Gelen malzeme kaydet
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Emanet ile kendi stoğu ayırır

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- 13.00.04

## Mevzuat
- Emanet stok muhasebe politikası

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
