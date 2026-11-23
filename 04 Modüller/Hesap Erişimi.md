---
tip: modul
kod: "15.02.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Hesap Erişimi

> Kod `15.02.01` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Müşteri reklam hesabı ve MCC/BM erişim durumu.

## Özellikler
### MVP
- Erişimi eksik hesapları göster
- Müşteri Z hesaplarını listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: haftalık. İşlem: kayıtlı hesap ile erişim durumunu karşılaştır. Çıktı: eksik veya yanlış hesap listesi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Meta Marketing API, Google Ads API

## Mevzuat
- Ticari Reklam ve Haksız Ticari Uygulamalar Yönetmeliği: reklam ajansı tanımı. Doğrulama kapanışı: Meta Marketing API genel bakışı ve Google Ads erişim seviyeleri (2026-11-19) açıldı. Seviyeler Test, Explorer, Basic ve Standard. Üretim hesabına yazmak başvuru ister. Doküman doğrulandı. Canlı kampanya yazması başvuru ve insan onayı olmadan gitmez.

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
