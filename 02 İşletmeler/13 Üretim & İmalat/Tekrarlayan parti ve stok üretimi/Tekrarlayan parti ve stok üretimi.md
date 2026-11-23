---
tip: isletme
kod: "13-02-01"
oneri_harf: B
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[13 Üretim & İmalat]]"
dal: "[[Dal – Tekrarlayan parti ve stok üretimi]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "C"
pazar_puani: 4
odeme_puani: 4
rekabet_puani: 2
kolaylik_puani: 3
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
  - "[[Parti Plan]]"
  - "[[Lot Barkod]]"
  - "[[Min Max]]"
  - "[[Verim Rapor]]"
  - "[[Alternatif Reçete]]"
rakipler:
  - "[[Mikro]]"
fonksiyonlar:
  - "[[SKU-A için 500'lük parti aç]]"
  - "[[Bu ay planı]]"
  - "[[Lot L-2411 oluştur]]"
  - "[[Lot L-2411 nereye gitti]]"
  - "[[Min altına düşenleri listele]]"
  - "[[Min 200 yap]]"
  - "[[SKU-B verim raporu]]"
  - "[[Alternatif reçeteyi uygula]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — uretim"
---
# 13-02-01 · Tekrarlayan parti ve stok üretimi

> Sektör: [[13 Üretim & İmalat]] · Öncelik: **3.4** / 5 · Öneri: **B**
> Puanlar tahmindir: pazar 4 · ödeme 4 · rekabet boşluğu 2 · kolaylık 3 · aciliyet 4

## 1. Özet
Kendi stok kodunu aynı reçeteyle partiler halinde yenileyen işletme.

- **İşletme sayısı:** bulunamadı
- **NACE:** C

## 2. Günlük iş akışı
1. Sabit reçete
2. parti miktarı
3. fire payı
4. ambar eşiği
5. sevkiyat.

```mermaid
flowchart LR
  S1["Sabit reçete"] --> S2
  S2["parti miktarı"] --> S3
  S3["fire payı"] --> S4
  S4["ambar eşiği"] --> S5
  S5["sevkiyat."]
```

AI destek (onaylı): Parti adedinden fireli malzeme ihtiyacını çıkarır; stok yetmezse eksiği listeler.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[İş Emri (Üretim)]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Reçete BOM]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Fire Kayıt]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Parti Plan]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Lot Barkod]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Min Max]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Verim Rapor]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Alternatif Reçete]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[İş Emri (Üretim)]] + [[Reçete BOM]] + [[Fire Kayıt]] + [[Depo Sevk]] + [[Fason Mutabakat]] + [[Parti Plan]] + [[Lot Barkod]]…

### Fonksiyonlar
- [[SKU-A için 500'lük parti aç]]
- [[Bu ay planı]]
- [[Lot L-2411 oluştur]]
- [[Lot L-2411 nereye gitti]]
- [[Min altına düşenleri listele]]
- [[Min 200 yap]]
- [[SKU-B verim raporu]]
- [[Alternatif reçeteyi uygula]]

### MVP
- [[İş Emri (Üretim)]]
- [[Reçete BOM]]
- [[Fire Kayıt]]
- [[Depo Sevk]]
- [[Fason Mutabakat]]
- [[Parti Plan]]
- [[Lot Barkod]]
- [[Min Max]]

### Sonraki sürüm
- [[Verim Rapor]]
- [[Alternatif Reçete]]

## 5. Teknik detay
- **Entegrasyonlar:** Barkod yazıcı, Mikro API, Mikro API (doğrulandı), Logo/Nebim (dogrulanmali), Mikro e-İrsaliye API, Mikro stok, Raporlar, e-Fatura, Mikro cari
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Tekrarlayan parti ve stok üretimi gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
