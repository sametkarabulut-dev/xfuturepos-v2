---
tip: isletme
kod: "13-01-01"
oneri_harf: A
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[13 Üretim & İmalat]]"
dal: "[[Dal – Siparişe göre kısa çevrim atölye]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "C"
pazar_puani: 5
odeme_puani: 4
rekabet_puani: 3
kolaylik_puani: 4
aciliyet_puani: 4
ihtiyaclar:
  - "[[İş emri]]"
  - "[[Reçete / BOM]]"
  - "[[Fire kaydı]]"
  - "[[Depo sevk]]"
  - "[[e-Belge / e-İrsaliye]]"
  - "[[Fason mutabakat]]"
  - "[[Lot / SKT]]"
  - "[[Gıda kayıt]]"
moduller:
  - "[[Muhasebe ve Gelir-Gider]]"
  - "[[e-Fatura ve e-Arşiv]]"
  - "[[CRM]]"
  - "[[Personel ve Vardiya]]"
  - "[[Raporlar]]"
  - "[[AI Asistan]]"
  - "[[Ayarlar]]"
  - "[[İş Emri (Üretim)]]"
  - "[[Reçete BOM]]"
  - "[[Fire Kayıt]]"
  - "[[Depo Sevk]]"
  - "[[Fason Mutabakat]]"
  - "[[Sipariş Emri]]"
  - "[[Atölye Kuyruk]]"
  - "[[Termin Alarm]]"
  - "[[Tezgah Yük]]"
  - "[[Revize Sipariş]]"
rakipler:
  - "[[Mikro]]"
fonksiyonlar:
  - "[[Sipariş 120'yi iş emrine çevir]]"
  - "[[Bugün teslimler]]"
  - "[[Torna kuyruğunu sırala]]"
  - "[[Acil işi öne al]]"
  - "[[Geç kalacak işleri söyle]]"
  - "[[Müşteri X gecikmeleri]]"
  - "[[Bu hafta freze doluluk]]"
  - "[[Sipariş 55 miktarı 80 yap]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — uretim"
---
# 13-01-01 · Siparişe göre kısa çevrim atölye

> Sektör: [[13 Üretim & İmalat]] · Öncelik: **4.0** / 5 · Öneri: **A**
> Puanlar tahmindir: pazar 5 · ödeme 4 · rekabet boşluğu 3 · kolaylık 4 · aciliyet 4

## 1. Özet
Müşterinin ölçüsüne göre saatler veya birkaç gün süren ayrı iş çıkaran atölye.

- **İşletme sayısı:** bulunamadı
- **NACE:** C

## 2. Günlük iş akışı
1. Teklif
2. eksik ölçü
3. iş emri
4. tezgâh sırası
5. fire
6. sevk.

```mermaid
flowchart LR
  S1["Teklif"] --> S2
  S2["eksik ölçü"] --> S3
  S3["iş emri"] --> S4
  S4["tezgâh sırası"] --> S5
  S5["fire"] --> S6
  S6["sevk."]
```

AI destek (onaylı): Serbest siparişten eksik ölçü ve termin listesi çıkarır; durum cümlesi taslaklar.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[İş Emri (Üretim)]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Reçete BOM]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Fire Kayıt]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Sipariş Emri]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Atölye Kuyruk]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Termin Alarm]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Tezgah Yük]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Revize Sipariş]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[İş Emri (Üretim)]] + [[Reçete BOM]] + [[Fire Kayıt]] + [[Depo Sevk]] + [[Fason Mutabakat]] + [[Sipariş Emri]] + [[Atölye Kuyruk]]…

### Fonksiyonlar
- [[Sipariş 120'yi iş emrine çevir]]
- [[Bugün teslimler]]
- [[Torna kuyruğunu sırala]]
- [[Acil işi öne al]]
- [[Geç kalacak işleri söyle]]
- [[Müşteri X gecikmeleri]]
- [[Bu hafta freze doluluk]]
- [[Sipariş 55 miktarı 80 yap]]

### MVP
- [[İş Emri (Üretim)]]
- [[Reçete BOM]]
- [[Fire Kayıt]]
- [[Depo Sevk]]
- [[Fason Mutabakat]]
- [[Sipariş Emri]]
- [[Atölye Kuyruk]]
- [[Termin Alarm]]

### Sonraki sürüm
- [[Tezgah Yük]]
- [[Revize Sipariş]]

## 5. Teknik detay
- **Entegrasyonlar:** CRM, Mikro API, Mikro API (doğrulandı), Logo/Nebim (dogrulanmali), Mikro e-İrsaliye API, e-Fatura, Mikro cari
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Siparişe göre kısa çevrim atölye gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
- [[Mikro]]

## 9. Kaynaklar
- [[13 Üretim & İmalat – Kaynaklar]]
- Arşiv: `08 Arşiv/eski-docs-sektorel-arastirma/ai-kaynak/13-uretim-imalat.md`
