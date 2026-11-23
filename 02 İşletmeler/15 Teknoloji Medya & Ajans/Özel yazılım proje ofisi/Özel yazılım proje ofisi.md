---
tip: isletme
kod: "15-01-01"
oneri_harf: A
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[15 Teknoloji Medya & Ajans]]"
dal: "[[Dal – Özel yazılım proje ofisi]]"
durum: tamamlandi
olcek: ['tek-kisilik', 'mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "62.01"
pazar_puani: 5
odeme_puani: 4
rekabet_puani: 2
kolaylik_puani: 3
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
  - "[[Sprint Tahtası]]"
  - "[[Kabul Kontrolü]]"
  - "[[Teknik Kapsam]]"
  - "[[Ortam Envanteri]]"
  - "[[Depo Bağlantısı]]"
rakipler:
  - "[[Meta Ads]]"
  - "[[Google Ads]]"
  - "[[GitHub / GitLab]]"
fonksiyonlar:
  - "[[Engelli işleri listele]]"
  - "[[Sprint bitiş özeti yaz]]"
  - "[[Kabul için eksikleri çıkar]]"
  - "[[UAT notlarını maddele]]"
  - "[[Bu talep teklifte var mı?]]"
  - "[[Kapsam dışı PR'ları işaretle]]"
  - "[[Müşteri ortam kartını özetle]]"
  - "[[Eksik erişimleri listele]]"
  - "[[Bu PR hangi işe ait?]]"
  - "[[Açık PR'ları işlere eşle]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — karma"
---
# 15-01-01 · Özel yazılım proje ofisi

> Sektör: [[15 Teknoloji Medya & Ajans]] · Öncelik: **3.6** / 5 · Öneri: **A**
> Puanlar tahmindir: pazar 5 · ödeme 4 · rekabet boşluğu 2 · kolaylık 3 · aciliyet 4

## 1. Özet
Müşteri sözleşmesiyle yazılım yazan veya mevcut uygulamayı uyarlayan ekip. Kendi ürününü abonelikle yayımlamaz.

- **İşletme sayısı:** bulunamadı
- **NACE:** 62.01

## 2. Günlük iş akışı
1. Teklif kapsamı
2. sprint
3. kabul
4. saat kaydı.

```mermaid
flowchart LR
  S1["Teklif kapsamı"] --> S2
  S2["sprint"] --> S3
  S3["kabul"] --> S4
  S4["saat kaydı."]
```

AI destek (onaylı): Toplantı ve yazışmadan kapsam maddesi çıkarır; teklifte olmayan işi işaretler.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Proje Kapsamı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Saat Kullanımı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Brief Onayı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Sprint Tahtası]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Kabul Kontrolü]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Teknik Kapsam]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Ortam Envanteri]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Depo Bağlantısı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Proje Kapsamı]] + [[Saat Kullanımı]] + [[Brief Onayı]] + [[Teslim Takvimi]] + [[Sözleşme Takibi]] + [[Kaynak Planı]] + [[Teklif Paketi]]…

### Fonksiyonlar
- [[Engelli işleri listele]]
- [[Sprint bitiş özeti yaz]]
- [[Kabul için eksikleri çıkar]]
- [[UAT notlarını maddele]]
- [[Bu talep teklifte var mı?]]
- [[Kapsam dışı PR'ları işaretle]]
- [[Müşteri ortam kartını özetle]]
- [[Eksik erişimleri listele]]
- [[Bu PR hangi işe ait?]]
- [[Açık PR'ları işlere eşle]]

### MVP
- [[Proje Kapsamı]]
- [[Saat Kullanımı]]
- [[Brief Onayı]]
- [[Teslim Takvimi]]
- [[Sözleşme Takibi]]
- [[Sprint Tahtası]]
- [[Kabul Kontrolü]]
- [[Teknik Kapsam]]

### Sonraki sürüm
- [[Kaynak Planı]]
- [[Teklif Paketi]]
- [[Ortam Envanteri]]
- [[Depo Bağlantısı]]

## 5. Teknik detay
- **Entegrasyonlar:** GitHub REST API, GitLab REST API v4
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Özel yazılım proje ofisi gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
