---
tip: isletme
kod: "16-05-01"
oneri_harf: B
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[16 Etkinlik & Organizasyon]]"
dal: "[[Dal – Sahne, ses ve ışık teknik hizmeti]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "90.02"
pazar_puani: 3
odeme_puani: 3
rekabet_puani: 3
kolaylik_puani: 4
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
  - "[[Ekipman çıkış]]"
  - "[[Kurulum pencere]]"
  - "[[Dönüş sayım]]"
rakipler:
  - "[[iyzico]]"
  - "[[Biletix / Passo]]"
fonksiyonlar:
  - "[[2x line array müsait mi?]]"
  - "[[Cumartesi çıkış listesi]]"
  - "[[Load-in 14–18 çakışıyor mu?]]"
  - "[[Kaç teknisyen?]]"
  - "[[Dönüşte eksik ne?]]"
  - "[[Hasar kaydı aç]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — etkinlik"
---
# 16-05-01 · Sahne, ses ve ışık teknik hizmeti

> Sektör: [[16 Etkinlik & Organizasyon]] · Öncelik: **3.2** / 5 · Öneri: **B**
> Puanlar tahmindir: pazar 3 · ödeme 3 · rekabet boşluğu 3 · kolaylık 4 · aciliyet 3

## 1. Özet
Gösterinin ses, ışık ve sahne tekniğini ekipman ve ekiple kuran firma.

- **İşletme sayısı:** bulunamadı
- **NACE:** 90.02

## 2. Günlük iş akışı
1. Depo çıkışı
2. kurulum penceresi
3. ekip çağrısı
4. söküm
5. dönüş sayımı.

```mermaid
flowchart LR
  S1["Depo çıkışı"] --> S2
  S2["kurulum penceresi"] --> S3
  S3["ekip çağrısı"] --> S4
  S4["söküm"] --> S5
  S5["dönüş sayımı."]
```

AI destek (onaylı): Teknik ister, çıkış fişi ve dönüş sayımını karşılaştırıp eksik dönen ekipmanı gösterir.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Etkinlik takvimi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Kapora sözleşme]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Tedarikçi teyidi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Ekipman çıkış]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Kurulum pencere]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Dönüş sayım]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Etkinlik takvimi]] + [[Kapora sözleşme]] + [[Tedarikçi teyidi]] + [[Run-of-show]] + [[Kişi sayısı]] + [[Ekipman çıkış]] + [[Kurulum pencere]]…

### Fonksiyonlar
- [[2x line array müsait mi?]]
- [[Cumartesi çıkış listesi]]
- [[Load-in 14–18 çakışıyor mu?]]
- [[Kaç teknisyen?]]
- [[Dönüşte eksik ne?]]
- [[Hasar kaydı aç]]

### MVP
- [[Etkinlik takvimi]]
- [[Kapora sözleşme]]
- [[Tedarikçi teyidi]]
- [[Run-of-show]]
- [[Kişi sayısı]]
- [[Ekipman çıkış]]
- [[Kurulum pencere]]
- [[Dönüş sayım]]

### Sonraki sürüm
- V2 opsiyonel araçlar

## 5. Teknik detay
- **Entegrasyonlar:** Panel takvimi, WhatsApp Cloud API, iyzico
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Sahne, ses ve ışık teknik hizmeti gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
