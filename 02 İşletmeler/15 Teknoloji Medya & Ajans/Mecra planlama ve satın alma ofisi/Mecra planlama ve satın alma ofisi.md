---
tip: isletme
kod: "15-05-01"
oneri_harf: C
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[15 Teknoloji Medya & Ajans]]"
dal: "[[Dal – Mecra planlama ve satın alma ofisi]]"
durum: tamamlandi
olcek: ['tek-kisilik', 'mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "73.12"
pazar_puani: 2
odeme_puani: 3
rekabet_puani: 2
kolaylik_puani: 2
aciliyet_puani: 3
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
  - "[[Mecra Planı]]"
  - "[[Sipariş Teyidi]]"
  - "[[Mecra Faturası]]"
  - "[[Plan Karşılaştırma]]"
rakipler:
  - "[[Meta Ads]]"
  - "[[Google Ads]]"
  - "[[GitHub / GitLab]]"
fonksiyonlar:
  - "[[Plan ile siparişi karşılaştır]]"
  - "[[Bu ayın mecra planını özetle]]"
  - "[[Teyidi gelmeyen siparişleri listele]]"
  - "[[Yayın teyidini eşle]]"
  - "[[Faturası gelmeyen siparişleri bul]]"
  - "[[Fatura farklarını listele]]"
  - "[[Sapma olan mecraları göster]]"
  - "[[Bütçe aşımını özetle]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — karma"
---
# 15-05-01 · Mecra planlama ve satın alma ofisi

> Sektör: [[15 Teknoloji Medya & Ajans]] · Öncelik: **2.4** / 5 · Öneri: **C**
> Puanlar tahmindir: pazar 2 · ödeme 3 · rekabet boşluğu 2 · kolaylık 2 · aciliyet 3

## 1. Özet
Müşteri bütçesini mecralara yerleştiren küçük ofis. Günü Ads Manager içinde geçmez.

- **İşletme sayısı:** bulunamadı
- **NACE:** 73.12

## 2. Günlük iş akışı
1. Plan
2. sipariş
3. yayın teyidi
4. mecra faturası.

```mermaid
flowchart LR
  S1["Plan"] --> S2
  S2["sipariş"] --> S3
  S3["yayın teyidi"] --> S4
  S4["mecra faturası."]
```

AI destek (onaylı): Sipariş, teyit ve fatura satırını eşleyip eksiği listeler.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Proje Kapsamı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Saat Kullanımı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Brief Onayı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Mecra Planı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Sipariş Teyidi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Mecra Faturası]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Plan Karşılaştırma]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Proje Kapsamı]] + [[Saat Kullanımı]] + [[Brief Onayı]] + [[Teslim Takvimi]] + [[Sözleşme Takibi]] + [[Kaynak Planı]] + [[Teklif Paketi]]…

### Fonksiyonlar
- [[Plan ile siparişi karşılaştır]]
- [[Bu ayın mecra planını özetle]]
- [[Teyidi gelmeyen siparişleri listele]]
- [[Yayın teyidini eşle]]
- [[Faturası gelmeyen siparişleri bul]]
- [[Fatura farklarını listele]]
- [[Sapma olan mecraları göster]]
- [[Bütçe aşımını özetle]]

### MVP
- [[Proje Kapsamı]]
- [[Saat Kullanımı]]
- [[Brief Onayı]]
- [[Teslim Takvimi]]
- [[Sözleşme Takibi]]
- [[Mecra Planı]]
- [[Sipariş Teyidi]]
- [[Mecra Faturası]]

### Sonraki sürüm
- [[Kaynak Planı]]
- [[Teklif Paketi]]
- [[Plan Karşılaştırma]]

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
- **Değer önerisi (tek cümle):** Mecra planlama ve satın alma ofisi gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
