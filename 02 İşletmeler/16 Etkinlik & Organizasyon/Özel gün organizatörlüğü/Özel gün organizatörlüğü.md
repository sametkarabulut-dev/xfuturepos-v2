---
tip: isletme
kod: "16-02-01"
oneri_harf: A
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[16 Etkinlik & Organizasyon]]"
dal: "[[Dal – Özel gün organizatörlüğü]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "82.30"
pazar_puani: 4
odeme_puani: 4
rekabet_puani: 3
kolaylik_puani: 4
aciliyet_puani: 4
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
  - "[[İş brief]]"
  - "[[Teklif karşılaştır]]"
  - "[[Gün checklist]]"
rakipler:
  - "[[iyzico]]"
  - "[[Biletix / Passo]]"
fonksiyonlar:
  - "[[Kına brief'i özetle]]"
  - "[[Bütçe tavanı aşıldı mı?]]"
  - "[[Üç fotoğraf teklifini karşılaştır]]"
  - "[[En ucuz ama teyitsiz kim?]]"
  - "[[Nikah günü checklist]]"
  - "[[Eksik teslim kalemi?]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — etkinlik"
---
# 16-02-01 · Özel gün organizatörlüğü

> Sektör: [[16 Etkinlik & Organizasyon]] · Öncelik: **3.8** / 5 · Öneri: **A**
> Puanlar tahmindir: pazar 4 · ödeme 4 · rekabet boşluğu 3 · kolaylık 4 · aciliyet 4

## 1. Özet
Çift veya aile adına günü planlayan, salonu işletmeyen firma.

- **İşletme sayısı:** bulunamadı
- **NACE:** 82.30

## 2. Günlük iş akışı
1. Brief
2. tedarikçi teyidi
3. kapora
4. günün akış çizelgesi.

```mermaid
flowchart LR
  S1["Brief"] --> S2
  S2["tedarikçi teyidi"] --> S3
  S3["kapora"] --> S4
  S4["günün akış çizelgesi."]
```

AI destek (onaylı): Gelen teklifleri kalemlere ayırır; teyitsiz veya saati çakışan kalemi gösterir.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Etkinlik takvimi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Kapora sözleşme]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Tedarikçi teyidi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[İş brief]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Teklif karşılaştır]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Gün checklist]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Etkinlik takvimi]] + [[Kapora sözleşme]] + [[Tedarikçi teyidi]] + [[Run-of-show]] + [[Kişi sayısı]] + [[İş brief]] + [[Teklif karşılaştır]]…

### Fonksiyonlar
- [[Kına brief'i özetle]]
- [[Bütçe tavanı aşıldı mı?]]
- [[Üç fotoğraf teklifini karşılaştır]]
- [[En ucuz ama teyitsiz kim?]]
- [[Nikah günü checklist]]
- [[Eksik teslim kalemi?]]

### MVP
- [[Etkinlik takvimi]]
- [[Kapora sözleşme]]
- [[Tedarikçi teyidi]]
- [[Run-of-show]]
- [[Kişi sayısı]]
- [[İş brief]]
- [[Teklif karşılaştır]]
- [[Gün checklist]]

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
- **Değer önerisi (tek cümle):** Özel gün organizatörlüğü gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
