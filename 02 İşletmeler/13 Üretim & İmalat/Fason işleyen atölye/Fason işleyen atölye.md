---
tip: isletme
kod: "13-03-01"
oneri_harf: A
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[13 Üretim & İmalat]]"
dal: "[[Dal – Fason işleyen atölye]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "C"
pazar_puani: 4
odeme_puani: 3
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
  - "[[Müşteri Malzeme]]"
  - "[[İşçilik Hakediş]]"
  - "[[Dönüş İrsaliye]]"
  - "[[Fire Bildirim]]"
  - "[[Kapasite Slot]]"
rakipler:
  - "[[Mikro]]"
fonksiyonlar:
  - "[[Müşteri Y kumaş bakiyesi]]"
  - "[[Gelen malzeme kaydet]]"
  - "[[Müşteri Y bu ay hakediş]]"
  - "[[Birim fiyat 4,5 TL]]"
  - "[[Mamulü müşteriye sevk et]]"
  - "[[İrsaliye hazırla]]"
  - "[[Fireyi müşteriye bildir]]"
  - "[[Perşembe boş slot]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — uretim"
---
# 13-03-01 · Fason işleyen atölye

> Sektör: [[13 Üretim & İmalat]] · Öncelik: **3.6** / 5 · Öneri: **A**
> Puanlar tahmindir: pazar 4 · ödeme 3 · rekabet boşluğu 3 · kolaylık 4 · aciliyet 4

## 1. Özet
Başkasının malını işleyip işçilik bedeli kesen atölye.

- **İşletme sayısı:** bulunamadı
- **NACE:** C

## 2. Günlük iş akışı
1. Gelen mal
2. işlem
3. fire mutabakatı
4. iade sevk
5. hizmet faturası.

```mermaid
flowchart LR
  S1["Gelen mal"] --> S2
  S2["işlem"] --> S3
  S3["fire mutabakatı"] --> S4
  S4["iade sevk"] --> S5
  S5["hizmet faturası."]
```

AI destek (onaylı): Gelen irsaliyeyi açık işe bağlar; iade ve fire farkını mutabakat metnine döker.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[İş Emri (Üretim)]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Reçete BOM]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Fire Kayıt]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Müşteri Malzeme]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[İşçilik Hakediş]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Dönüş İrsaliye]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Fire Bildirim]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Kapasite Slot]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[İş Emri (Üretim)]] + [[Reçete BOM]] + [[Fire Kayıt]] + [[Depo Sevk]] + [[Fason Mutabakat]] + [[Müşteri Malzeme]] + [[İşçilik Hakediş]]…

### Fonksiyonlar
- [[Müşteri Y kumaş bakiyesi]]
- [[Gelen malzeme kaydet]]
- [[Müşteri Y bu ay hakediş]]
- [[Birim fiyat 4,5 TL]]
- [[Mamulü müşteriye sevk et]]
- [[İrsaliye hazırla]]
- [[Fireyi müşteriye bildir]]
- [[Perşembe boş slot]]

### MVP
- [[İş Emri (Üretim)]]
- [[Reçete BOM]]
- [[Fire Kayıt]]
- [[Depo Sevk]]
- [[Fason Mutabakat]]
- [[Müşteri Malzeme]]
- [[İşçilik Hakediş]]
- [[Dönüş İrsaliye]]

### Sonraki sürüm
- [[Fire Bildirim]]
- [[Kapasite Slot]]

## 5. Teknik detay
- **Entegrasyonlar:** 13.00.04, Mikro API, Mikro API (doğrulandı), Logo/Nebim (dogrulanmali), Mikro e-İrsaliye API, e-Fatura, e-Fatura, Mikro cari
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Fason işleyen atölye gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
