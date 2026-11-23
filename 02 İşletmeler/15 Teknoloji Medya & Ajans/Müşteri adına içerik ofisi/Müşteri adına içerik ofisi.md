---
tip: isletme
kod: "15-03-01"
oneri_harf: A
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[15 Teknoloji Medya & Ajans]]"
dal: "[[Dal – Müşteri adına içerik ofisi]]"
durum: tamamlandi
olcek: ['tek-kisilik', 'mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "73.11"
pazar_puani: 4
odeme_puani: 3
rekabet_puani: 3
kolaylik_puani: 4
aciliyet_puani: 4
ihtiyaclar:
  - "[[Proje kapsamı]]"
  - "[[Saat kullanımı]]"
  - "[[Brief / onay]]"
  - "[[Teslim takvimi]]"
  - "[[Sözleşme / retainer]]"
  - "[[e-Belge]]"
  - "[[Reklam hesabı erişimi]]"
  - "[[Yayın takvimi]]"
moduller:
  - "[[Muhasebe ve Gelir-Gider]]"
  - "[[e-Fatura ve e-Arşiv]]"
  - "[[CRM]]"
  - "[[Personel ve Vardiya]]"
  - "[[Raporlar]]"
  - "[[AI Asistan]]"
  - "[[Ayarlar]]"
  - "[[Proje Kapsamı]]"
  - "[[Saat Kullanımı]]"
  - "[[Brief Onayı]]"
  - "[[Teslim Takvimi]]"
  - "[[Sözleşme Takibi]]"
  - "[[Kaynak Planı]]"
  - "[[Teklif Paketi]]"
  - "[[Yayın Takvimi]]"
  - "[[İçerik Onayı]]"
  - "[[Kanal Listesi]]"
  - "[[SEO İşleri]]"
  - "[[Etkileşim Özeti]]"
rakipler:
  - "[[Meta Ads]]"
  - "[[Google Ads]]"
  - "[[GitHub / GitLab]]"
fonksiyonlar:
  - "[[Bu hafta boş kalan günleri göster]]"
  - "[[Onaysız içerikleri listele]]"
  - "[[Onayı bekleyen içerikleri sırala]]"
  - "[[Brief'ten taslak üret]]"
  - "[[Müşteri kanallarını listele]]"
  - "[[Erişimi belirsiz kanalları bul]]"
  - "[[Bu ayın SEO işlerini özetle]]"
  - "[[Yarım kalan sayfa işlerini listele]]"
  - "[[Müşteri B için etkileşim özeti yaz]]"
  - "[[Düşen kanalları işaretle]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — karma"
---
# 15-03-01 · Müşteri adına içerik ofisi

> Sektör: [[15 Teknoloji Medya & Ajans]] · Öncelik: **3.6** / 5 · Öneri: **A**
> Puanlar tahmindir: pazar 4 · ödeme 3 · rekabet boşluğu 3 · kolaylık 4 · aciliyet 4

## 1. Özet
Müşterinin kanalında takvimle yayın yapan retainer ofis. Reklam hesabı asıl işi değildir.

- **İşletme sayısı:** bulunamadı
- **NACE:** 73.11

## 2. Günlük iş akışı
1. Takvim
2. onay
3. yayın
4. aylık iş listesi.

```mermaid
flowchart LR
  S1["Takvim"] --> S2
  S2["onay"] --> S3
  S3["yayın"] --> S4
  S4["aylık iş listesi."]
```

AI destek (onaylı): Onayı bekleyen ve takvimi boş işleri özetler; brief’ten yayın taslağı üretir.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Proje Kapsamı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Saat Kullanımı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Brief Onayı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Yayın Takvimi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[İçerik Onayı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Kanal Listesi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[SEO İşleri]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Etkileşim Özeti]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Proje Kapsamı]] + [[Saat Kullanımı]] + [[Brief Onayı]] + [[Teslim Takvimi]] + [[Sözleşme Takibi]] + [[Kaynak Planı]] + [[Teklif Paketi]]…

### Fonksiyonlar
- [[Bu hafta boş kalan günleri göster]]
- [[Onaysız içerikleri listele]]
- [[Onayı bekleyen içerikleri sırala]]
- [[Brief'ten taslak üret]]
- [[Müşteri kanallarını listele]]
- [[Erişimi belirsiz kanalları bul]]
- [[Bu ayın SEO işlerini özetle]]
- [[Yarım kalan sayfa işlerini listele]]
- [[Müşteri B için etkileşim özeti yaz]]
- [[Düşen kanalları işaretle]]

### MVP
- [[Proje Kapsamı]]
- [[Saat Kullanımı]]
- [[Brief Onayı]]
- [[Teslim Takvimi]]
- [[Sözleşme Takibi]]
- [[Yayın Takvimi]]
- [[İçerik Onayı]]
- [[Kanal Listesi]]

### Sonraki sürüm
- [[Kaynak Planı]]
- [[Teklif Paketi]]
- [[SEO İşleri]]
- [[Etkileşim Özeti]]

## 5. Teknik detay
- **Entegrasyonlar:** Panel kaydı
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Müşteri adına içerik ofisi gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
- **3 ana mesaj:**
  1. Dağınık Excel/WhatsApp yerine tek iş kaydı
  2. e-Belge ve hatırlatmalar onay kuyruğunda
  3. Sektöre özel alanlar, ortak çekirdek üzerinde
- **İtirazlar ve cevaplar:**

| İtiraz | Cevap |
|---|---|
| Zaten Excel var | Süre/uyum hatırlatması ve belge taslağı Excel’de dağılır |
| Resmi API yok | Panel kaydı + kurum portalı; uydurma entegrasyon yok |
| Pahalı | Taahhütsüz paket; yalnız kullanılan araçlar (tahmin) |

## 8. Rakipler
- [[Meta Ads]]
- [[Google Ads]]
- [[GitHub / GitLab]]

## 9. Kaynaklar
- [[15 Teknoloji Medya & Ajans – Kaynaklar]]
- Arşiv: `08 Arşiv/eski-docs-sektorel-arastirma/ai-kaynak/15-teknoloji-medya-ajans.md`
