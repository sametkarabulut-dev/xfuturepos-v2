---
tip: modul
kod: "15.02.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Dönem Raporu

> Kod `15.02.03` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Dönem harcama, tıklama ve dönüşüm özeti.

## Özellikler
### MVP
- Müşteri A için aylık rapor taslağı
- Hesaplar arası harcamayı karşılaştır
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: dönem sonu. İşlem: metrikleri topla. Çıktı: müşteri rapor taslağı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Meta Marketing API, Google Ads API

## Mevzuat
- Ticari Reklam Yönetmeliği kapsamında reklam ajansı. Doğrulama kapanışı: Meta Marketing API genel bakışı ve Google Ads erişim seviyeleri (2026-11-19) açıldı. Seviyeler Test, Explorer, Basic ve Standard. Üretim hesabına yazmak başvuru ister. Doküman doğrulandı. Canlı kampanya yazması başvuru ve insan onayı olmadan gitmez.

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
