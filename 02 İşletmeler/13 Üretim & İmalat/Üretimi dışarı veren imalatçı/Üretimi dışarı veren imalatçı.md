---
tip: isletme
kod: "13-06-01"
oneri_harf: B
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[13 Üretim & İmalat]]"
dal: "[[Dal – Üretimi dışarı veren imalatçı]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "C"
pazar_puani: 3
odeme_puani: 3
rekabet_puani: 3
kolaylik_puani: 3
aciliyet_puani: 3
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
  - "[[Fasoncu Sevk]]"
  - "[[Dönüş Kabul]]"
  - "[[Hakediş Kesinti]]"
  - "[[Fasoncu Bakiye]]"
  - "[[Çok Fasoncu]]"
rakipler:
  - "[[Mikro]]"
fonksiyonlar:
  - "[[ABC'ye 405 kg kumaş sevk et]]"
  - "[[Açık sevkler]]"
  - "[[ABC dönüşünü kaydet 960 adet]]"
  - "[[Ret 40]]"
  - "[[ABC hakedişini kesintili hesapla]]"
  - "[[Kimde ne malzeme var]]"
  - "[[Kesim ABC, dikim DEF]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — uretim"
---
# 13-06-01 · Üretimi dışarı veren imalatçı

> Sektör: [[13 Üretim & İmalat]] · Öncelik: **3.0** / 5 · Öneri: **B**
> Puanlar tahmindir: pazar 3 · ödeme 3 · rekabet boşluğu 3 · kolaylık 3 · aciliyet 3

## 1. Özet
Kendi modelinin dönüşümünü başka atölyede yaptıran, kendi tezgâhı merkez olmayan imalatçı.

- **İşletme sayısı:** bulunamadı
- **NACE:** C

## 2. Günlük iş akışı
1. Malzeme çıkışı
2. fason emri
3. dışarıdaki stok
4. geri kabul
5. işçilik faturası.

```mermaid
flowchart LR
  S1["Malzeme çıkışı"] --> S2
  S2["fason emri"] --> S3
  S3["dışarıdaki stok"] --> S4
  S4["geri kabul"] --> S5
  S5["işçilik faturası."]
```

AI destek (onaylı): Gönderilen malzeme ile geri gelen mamulü karşılaştırıp geciken fason için takip metni yazar.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[İş Emri (Üretim)]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Reçete BOM]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Fire Kayıt]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Fasoncu Sevk]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Dönüş Kabul]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Hakediş Kesinti]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Fasoncu Bakiye]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Çok Fasoncu]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[İş Emri (Üretim)]] + [[Reçete BOM]] + [[Fire Kayıt]] + [[Depo Sevk]] + [[Fason Mutabakat]] + [[Fasoncu Sevk]] + [[Dönüş Kabul]]…

### Fonksiyonlar
- [[ABC'ye 405 kg kumaş sevk et]]
- [[Açık sevkler]]
- [[ABC dönüşünü kaydet 960 adet]]
- [[Ret 40]]
- [[ABC hakedişini kesintili hesapla]]
- [[Kimde ne malzeme var]]
- [[Kesim ABC, dikim DEF]]

### MVP
- [[İş Emri (Üretim)]]
- [[Reçete BOM]]
- [[Fire Kayıt]]
- [[Depo Sevk]]
- [[Fason Mutabakat]]
- [[Fasoncu Sevk]]
- [[Dönüş Kabul]]
- [[Hakediş Kesinti]]

### Sonraki sürüm
- [[Fasoncu Bakiye]]
- [[Çok Fasoncu]]

## 5. Teknik detay
- **Entegrasyonlar:** 13.00.03, 13.00.05, Mikro API, Mikro API (doğrulandı), Logo/Nebim (dogrulanmali), Mikro e-İrsaliye API, e-Fatura, Mikro cari, e-Fatura, Muhasebe
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Üretimi dışarı veren imalatçı gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
