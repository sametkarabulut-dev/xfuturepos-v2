---
tip: isletme
kod: "15-04-01"
oneri_harf: B
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[15 Teknoloji Medya & Ajans]]"
dal: "[[Dal – Marka, tasarım ve görüntü stüdyosu]]"
durum: tamamlandi
olcek: ['tek-kisilik', 'mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "74.10"
pazar_puani: 4
odeme_puani: 3
rekabet_puani: 3
kolaylik_puani: 4
aciliyet_puani: 3
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
  - "[[Varlık Sürümü]]"
  - "[[Revizyon Turu]]"
  - "[[Hak Listesi]]"
  - "[[Çekim Planı]]"
  - "[[Arşiv Dolabı]]"
rakipler:
  - "[[Meta Ads]]"
  - "[[Google Ads]]"
  - "[[GitHub / GitLab]]"
fonksiyonlar:
  - "[[Final sürümü bul]]"
  - "[[Eski sürümleri arşiv öner]]"
  - "[[Revizyon notlarını maddele]]"
  - "[[Sözleşmedeki tur aşıldı mı?]]"
  - "[[Hak listesi eksik mi?]]"
  - "[[5846 hak maddelerini doldur]]"
  - "[[Yarınki çekim checklist'i]]"
  - "[[Eksik ekipmanı listele]]"
  - "[[Lisansı belirsiz stokları bul]]"
  - "[[Proje arşivini özetle]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — karma"
---
# 15-04-01 · Marka, tasarım ve görüntü stüdyosu

> Sektör: [[15 Teknoloji Medya & Ajans]] · Öncelik: **3.4** / 5 · Öneri: **B**
> Puanlar tahmindir: pazar 4 · ödeme 3 · rekabet boşluğu 3 · kolaylık 4 · aciliyet 3

## 1. Özet
Brief ile marka dili, grafik veya reklam filmi teslim eden stüdyo.

- **İşletme sayısı:** bulunamadı
- **NACE:** 74.10

## 2. Günlük iş akışı
1. Brief
2. sürüm
3. revizyon
4. teslim
5. hak kapsamı.

```mermaid
flowchart LR
  S1["Brief"] --> S2
  S2["sürüm"] --> S3
  S3["revizyon"] --> S4
  S4["teslim"] --> S5
  S5["hak kapsamı."]
```

AI destek (onaylı): Revizyon notunu maddeler; teslimde hak listesinin eksik satırını işaretler.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Proje Kapsamı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Saat Kullanımı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Brief Onayı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Varlık Sürümü]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Revizyon Turu]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Hak Listesi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Çekim Planı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Arşiv Dolabı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Proje Kapsamı]] + [[Saat Kullanımı]] + [[Brief Onayı]] + [[Teslim Takvimi]] + [[Sözleşme Takibi]] + [[Kaynak Planı]] + [[Teklif Paketi]]…

### Fonksiyonlar
- [[Final sürümü bul]]
- [[Eski sürümleri arşiv öner]]
- [[Revizyon notlarını maddele]]
- [[Sözleşmedeki tur aşıldı mı?]]
- [[Hak listesi eksik mi?]]
- [[5846 hak maddelerini doldur]]
- [[Yarınki çekim checklist'i]]
- [[Eksik ekipmanı listele]]
- [[Lisansı belirsiz stokları bul]]
- [[Proje arşivini özetle]]

### MVP
- [[Proje Kapsamı]]
- [[Saat Kullanımı]]
- [[Brief Onayı]]
- [[Teslim Takvimi]]
- [[Sözleşme Takibi]]
- [[Varlık Sürümü]]
- [[Revizyon Turu]]
- [[Hak Listesi]]

### Sonraki sürüm
- [[Kaynak Planı]]
- [[Teklif Paketi]]
- [[Çekim Planı]]
- [[Arşiv Dolabı]]

## 5. Teknik detay
- **Entegrasyonlar:** Çekirdek e-belge entegratörü; sektörel API yoksa panel kaydı
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** Marka, tasarım ve görüntü stüdyosu gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
