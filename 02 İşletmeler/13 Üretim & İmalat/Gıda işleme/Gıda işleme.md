---
tip: isletme
kod: "13-05-01"
oneri_harf: C
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[13 Üretim & İmalat]]"
dal: "[[Dal – Gıda işleme]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "10"
pazar_puani: 3
odeme_puani: 3
rekabet_puani: 2
kolaylik_puani: 2
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
  - "[[Lot İzle]]"
  - "[[SKT Parti]]"
  - "[[Kayıt Onay]]"
  - "[[Soğuk Kayıt]]"
  - "[[Geri Çağır]]"
rakipler:
  - "[[Mikro]]"
fonksiyonlar:
  - "[[Lot G-90 nereye gitti]]"
  - "[[Bu satışın hammaddesi]]"
  - "[[SKT'si 7 gün kalanlar]]"
  - "[[FEFO ile sevk]]"
  - "[[Kayıt belgesi bitiş tarihi]]"
  - "[[Onay kapsamım ne]]"
  - "[[Soğuk oda bugün kaydı]]"
  - "[[Lot G-90 geri çağır]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — uretim"
---
# 13-05-01 · Gıda işleme

> Sektör: [[13 Üretim & İmalat]] · Öncelik: **2.8** / 5 · Öneri: **C**
> Puanlar tahmindir: pazar 3 · ödeme 3 · rekabet boşluğu 2 · kolaylık 2 · aciliyet 4

## 1. Özet
Bozulabilir girdiyi reçete ve parti ile işleyip piyasaya gıda arz eden işletme. Lokanta burada değildir.

- **İşletme sayısı:** bulunamadı
- **NACE:** 10

## 2. Günlük iş akışı
1. Reçete
2. lot
3. son tüketim tarihi
4. verim
5. kayıt veya onay dosyası.

```mermaid
flowchart LR
  S1["Reçete"] --> S2
  S2["lot"] --> S3
  S3["son tüketim tarihi"] --> S4
  S4["verim"] --> S5
  S5["kayıt veya onay dosyası."]
```

AI destek (onaylı): Günün partisinden lot ve tüketim dökümünü taslaklar; tarihi yaklaşmış girdiyi işaretler.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[İş Emri (Üretim)]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Reçete BOM]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Fire Kayıt]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Lot İzle]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[SKT Parti]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Kayıt Onay]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Soğuk Kayıt]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Geri Çağır]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[İş Emri (Üretim)]] + [[Reçete BOM]] + [[Fire Kayıt]] + [[Depo Sevk]] + [[Fason Mutabakat]] + [[Lot İzle]] + [[SKT Parti]]…

### Fonksiyonlar
- [[Lot G-90 nereye gitti]]
- [[Bu satışın hammaddesi]]
- [[SKT'si 7 gün kalanlar]]
- [[FEFO ile sevk]]
- [[Kayıt belgesi bitiş tarihi]]
- [[Onay kapsamım ne]]
- [[Soğuk oda bugün kaydı]]
- [[Lot G-90 geri çağır]]

### MVP
- [[İş Emri (Üretim)]]
- [[Reçete BOM]]
- [[Fire Kayıt]]
- [[Depo Sevk]]
- [[Fason Mutabakat]]
- [[Lot İzle]]
- [[SKT Parti]]
- [[Kayıt Onay]]

### Sonraki sürüm
- [[Soğuk Kayıt]]
- [[Geri Çağır]]

## 5. Teknik detay
- **Entegrasyonlar:** 13.00.04, 13.02.02, CRM, e-İrsaliye, Elle sıcaklık, Mikro API, Mikro API (doğrulandı), Logo/Nebim (dogrulanmali), Mikro e-İrsaliye API, e-Fatura, Mikro cari
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Gıda işleme gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
