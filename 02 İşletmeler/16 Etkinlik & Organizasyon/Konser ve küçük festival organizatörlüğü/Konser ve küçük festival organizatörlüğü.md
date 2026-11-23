---
tip: isletme
kod: "16-04-01"
oneri_harf: C
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[16 Etkinlik & Organizasyon]]"
dal: "[[Dal – Konser ve küçük festival organizatörlüğü]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "90.02"
pazar_puani: 2
odeme_puani: 3
rekabet_puani: 2
kolaylik_puani: 2
aciliyet_puani: 3
ihtiyaclar:
  - "[[Etkinlik takvimi]]"
  - "[[Kapora / sözleşme]]"
  - "[[Tedarikçi teyidi]]"
  - "[[Run-of-show]]"
  - "[[Kişi sayısı]]"
  - "[[e-Belge]]"
  - "[[Salon seans]]"
  - "[[Telif / MSG listesi]]"
moduller:
  - "[[Muhasebe ve Gelir-Gider]]"
  - "[[e-Fatura ve e-Arşiv]]"
  - "[[CRM]]"
  - "[[Personel ve Vardiya]]"
  - "[[Raporlar]]"
  - "[[AI Asistan]]"
  - "[[Ayarlar]]"
  - "[[Etkinlik takvimi]]"
  - "[[Kapora sözleşme]]"
  - "[[Tedarikçi teyidi]]"
  - "[[Run-of-show]]"
  - "[[Kişi sayısı]]"
  - "[[Gösteri dosya]]"
  - "[[Telif bildirim]]"
  - "[[Hasılat izin]]"
rakipler:
  - "[[iyzico]]"
  - "[[Biletix / Passo]]"
fonksiyonlar:
  - "[[Cuma teknik rider eksikleri?]]"
  - "[[Sanatçı çağrı saati?]]"
  - "[[MSG bildirim taslağı hazırla]]"
  - "[[Eser listesi eksik sanatçı?]]"
  - "[[Ön satış kaç?]]"
  - "[[Özel güvenlik başvurusu yapıldı mı?]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — etkinlik"
---
# 16-04-01 · Konser ve küçük festival organizatörlüğü

> Sektör: [[16 Etkinlik & Organizasyon]] · Öncelik: **2.4** / 5 · Öneri: **C**
> Puanlar tahmindir: pazar 2 · ödeme 3 · rekabet boşluğu 2 · kolaylık 2 · aciliyet 3

## 1. Özet
Yerel konseri veya küçük festivali üreten organizatör. Stadyum işletmeciliği dışarıdadır.

- **İşletme sayısı:** bulunamadı
- **NACE:** 90.02

## 2. Günlük iş akışı
1. Gösteri tarihi
2. sanatçı
3. teknik ister
4. hasılat
5. eser listesi
6. özel güvenlik talebi.

```mermaid
flowchart LR
  S1["Gösteri tarihi"] --> S2
  S2["sanatçı"] --> S3
  S3["teknik ister"] --> S4
  S4["hasılat"] --> S5
  S5["eser listesi"] --> S6
  S6["özel güvenlik talebi."]
```

AI destek (onaylı): Eser listesini MSG bildirim taslağına dizer; salon, belediye alanı ve güvenlik kalemlerini ayrı hatırlatır.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Etkinlik takvimi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Kapora sözleşme]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Tedarikçi teyidi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Gösteri dosya]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Telif bildirim]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Hasılat izin]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Etkinlik takvimi]] + [[Kapora sözleşme]] + [[Tedarikçi teyidi]] + [[Run-of-show]] + [[Kişi sayısı]] + [[Gösteri dosya]] + [[Telif bildirim]]…

### Fonksiyonlar
- [[Cuma teknik rider eksikleri?]]
- [[Sanatçı çağrı saati?]]
- [[MSG bildirim taslağı hazırla]]
- [[Eser listesi eksik sanatçı?]]
- [[Ön satış kaç?]]
- [[Özel güvenlik başvurusu yapıldı mı?]]

### MVP
- [[Etkinlik takvimi]]
- [[Kapora sözleşme]]
- [[Tedarikçi teyidi]]
- [[Run-of-show]]
- [[Kişi sayısı]]
- [[Gösteri dosya]]
- [[Telif bildirim]]
- [[Hasılat izin]]

### Sonraki sürüm
- V2 opsiyonel araçlar

## 5. Teknik detay
- **Entegrasyonlar:** Elle hasılat, MSG bildirim formu, Panel takvimi, WhatsApp Cloud API, iyzico
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Konser ve küçük festival organizatörlüğü gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
- [[iyzico]]
- [[Biletix / Passo]]

## 9. Kaynaklar
- [[16 Etkinlik & Organizasyon – Kaynaklar]]
- Arşiv: `08 Arşiv/eski-docs-sektorel-arastirma/ai-kaynak/16-etkinlik-organizasyon.md`
