---
tip: modul
kod: "13.00.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Reçete BOM

> Kod `13.00.02` · [[13 Üretim & İmalat]]

## Ne yapar
- Hammadde, birim, beklenen fire oranı; iş emrine bağlanır

## Özellikler
### MVP
- Gömlek reçetesini göster
- Fire oranını yüzde 5 yap
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- İş emri açılışında malzeme ihtiyacı ve stok yetersizliği uyarısı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Mikro API

## Mevzuat
- Doğrulama kapanışı: Mikro API açıldı: UrunReceteKaydetV2 ve StokKaydetV2. Logo ve Nebim için kamuya açık reçete ucu bu turda yok, listeden çıktı.

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
