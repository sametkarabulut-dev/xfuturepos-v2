---
tip: modul
kod: "15.02.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Dönüşüm İzleme

> Kod `15.02.05` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Dönüşüm ve etiket eşleme kontrolü.

## Özellikler
### MVP
- Eksik dönüşüm etiketlerini bul
- Son 7 gün dönüşüm düşüşünü özetle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: haftalık. İşlem: beklenen ile gelen dönüşümü karşılaştır. Çıktı: eksik izleme listesi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Meta Marketing API, Google Ads API

## Mevzuat
- Doğrulama kapanışı: Meta Marketing API genel bakışı ve Google Ads erişim seviyeleri (2026-11-19) açıldı. Seviyeler Test, Explorer, Basic ve Standard. Üretim hesabına yazmak başvuru ister. Doküman doğrulandı. Canlı kampanya yazması başvuru ve insan onayı olmadan gitmez.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[15 Teknoloji Medya & Ajans]]:** sektör/alt araç

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
