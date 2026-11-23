---
tip: modul
kod: "16.00.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Kişi sayısı

> Kod `16.00.05` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- Sözleşme kişi sayısı ile güncel sayıyı ve etkileri takip eder.

## Özellikler
### MVP
- Kişi 180'den 220'ye çıktı, ne değişir?
- Son kişi güncellemesi?
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Δ kişi ile menü/kapasite/ekip uyarıları üretir.

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
