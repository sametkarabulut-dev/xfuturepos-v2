---
tip: isletme
kod: "16-06-01"
oneri_harf: B
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[16 Etkinlik & Organizasyon]]"
dal: "[[Dal – Etkinlik ikramı]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "56.21"
pazar_puani: 3
odeme_puani: 3
rekabet_puani: 3
kolaylik_puani: 3
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
  - "[[Menü maliyet]]"
  - "[[Üretim sevkiyat]]"
  - "[[Gıda kayıt]]"
rakipler:
  - "[[iyzico]]"
  - "[[Biletix / Passo]]"
fonksiyonlar:
  - "[[220 kişilik menü maliyeti?]]"
  - "[[Vejetaryen 30 kişi ekle]]"
  - "[[Cumartesi üretim planı]]"
  - "[[Kap-kacak döndü mü?]]"
  - "[[Gıda kayıt numarası?]]"
  - "[[Belge adresi değişti mi?]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — etkinlik"
---
# 16-06-01 · Etkinlik ikramı

> Sektör: [[16 Etkinlik & Organizasyon]] · Öncelik: **3.0** / 5 · Öneri: **B**
> Puanlar tahmindir: pazar 3 · ödeme 3 · rekabet boşluğu 3 · kolaylık 3 · aciliyet 3

## 1. Özet
Müşterinin belirlediği etkinlikte sözleşmeyle yemek üreten işletme. Lokanta ve tabldot burada değildir.

- **İşletme sayısı:** bulunamadı
- **NACE:** 56.21

## 2. Günlük iş akışı
1. Tarih
2. kişi sayısı
3. menü maliyeti
4. üretim
5. taşıma
6. servis ekibi
7. kap dönüşü.

```mermaid
flowchart LR
  S1["Tarih"] --> S2
  S2["kişi sayısı"] --> S3
  S3["menü maliyeti"] --> S4
  S4["üretim"] --> S5
  S5["taşıma"] --> S6
  S6["servis ekibi"] --> S7
  S7["kap dönüşü."]
```

AI destek (onaylı): Kişi sayısı değişince reçeteden üretim miktarını ve servis ekibi ihtiyacını yeniden hesaplar.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Etkinlik takvimi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Kapora sözleşme]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Tedarikçi teyidi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Menü maliyet]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Üretim sevkiyat]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Gıda kayıt]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Etkinlik takvimi]] + [[Kapora sözleşme]] + [[Tedarikçi teyidi]] + [[Run-of-show]] + [[Kişi sayısı]] + [[Menü maliyet]] + [[Üretim sevkiyat]]…

### Fonksiyonlar
- [[220 kişilik menü maliyeti?]]
- [[Vejetaryen 30 kişi ekle]]
- [[Cumartesi üretim planı]]
- [[Kap-kacak döndü mü?]]
- [[Gıda kayıt numarası?]]
- [[Belge adresi değişti mi?]]

### MVP
- [[Etkinlik takvimi]]
- [[Kapora sözleşme]]
- [[Tedarikçi teyidi]]
- [[Run-of-show]]
- [[Kişi sayısı]]
- [[Menü maliyet]]
- [[Üretim sevkiyat]]
- [[Gıda kayıt]]

### Sonraki sürüm
- V2 opsiyonel araçlar

## 5. Teknik detay
- **Entegrasyonlar:** Panel takvimi, WhatsApp Cloud API, e-Devlet gıda kayıt, iyzico
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Etkinlik ikramı gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
