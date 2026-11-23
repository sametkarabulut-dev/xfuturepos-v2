---
tip: modul
kod: "09.05.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Kanal Yönetimi

> Kod `09.05.05` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- OTA/ilan kanallarında takvim/fiyat senkron uyumsuzluk takibi.

## Özellikler
### MVP
- Kanallardaki fiyat farklarını göster
- Overbooking riskini tara
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: takvim değişimi → İşlem: kanal uyumsuzluk tespiti → Çıktı: senkron uyarı kartı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Kanal durumu (elle)

## Mevzuat
- Platform API erişimi hesap/ortaklık bazlı; kamuya açık doğrulanmadı. Doğrulama kapanışı: Airbnb ve Booking.com için herkese açık uç bu turda açılmadı. Kanal durumu elle işlenir.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[09 Emlak & Gayrimenkul]]:** sektör/alt araç

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
