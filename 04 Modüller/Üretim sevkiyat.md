---
tip: modul
kod: "16.06.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Üretim sevkiyat

> Kod `16.06.02` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- Mutfak planı, taşıma, servis ekibi, kap-kacak dönüşü.

## Özellikler
### MVP
- Cumartesi üretim planı
- Kap-kacak döndü mü?
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Sevkiyat −1 gün ekip/araç hatırlatması.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yok / panel kaydı

## Yeniden kullanım
- **Araç türü:** ozel
- **[[16 Etkinlik & Organizasyon]]:** sektör/alt araç

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
