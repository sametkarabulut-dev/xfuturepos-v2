---
tip: isletme
kod: "15-06-01"
oneri_harf: C
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[15 Teknoloji Medya & Ajans]]"
dal: "[[Dal – Kendi mecrasını işleten yayıncı]]"
durum: tamamlandi
olcek: ['tek-kisilik', 'mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "58 / 63"
pazar_puani: 2
odeme_puani: 3
rekabet_puani: 2
kolaylik_puani: 2
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
  - "[[Yayın Masası]]"
  - "[[İlan Envanteri]]"
  - "[[Yasal Bilgi]]"
  - "[[Yayın İlan Eşleme]]"
rakipler:
  - "[[Meta Ads]]"
  - "[[Google Ads]]"
  - "[[GitHub / GitLab]]"
fonksiyonlar:
  - "[[Yarınki yayın sırasını göster]]"
  - "[[Boş yayın slotlarını listele]]"
  - "[[Satılmamış envanteri göster]]"
  - "[[Bu hafta satılan ilanları özetle]]"
  - "[[5651 bilgilendirme eksik mi?]]"
  - "[[İletişim bilgisi güncelliğini kontrol et]]"
  - "[[Yayına denk gelmeyen ilanları bul]]"
  - "[[Çakışan slotları listele]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — karma"
---
# 15-06-01 · Kendi mecrasını işleten yayıncı

> Sektör: [[15 Teknoloji Medya & Ajans]] · Öncelik: **2.4** / 5 · Öneri: **C**
> Puanlar tahmindir: pazar 2 · ödeme 3 · rekabet boşluğu 2 · kolaylık 2 · aciliyet 3

## 1. Özet
Kendi yayın takvimini yürüten ve kendi alan veya zamanını satan küçük dijital yayın.

- **İşletme sayısı:** bulunamadı
- **NACE:** 58 / 63

## 2. Günlük iş akışı
1. Yayın planı
2. içerik
3. kendi reklam envanteri.

```mermaid
flowchart LR
  S1["Yayın planı"] --> S2
  S2["içerik"] --> S3
  S3["kendi reklam envanteri."]
```

AI destek (onaylı): Plan boşluğu ile satılmış ilanın yayına denk gelip gelmediğini özetler.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Proje Kapsamı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Saat Kullanımı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Brief Onayı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Yayın Masası]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[İlan Envanteri]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Yasal Bilgi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Yayın İlan Eşleme]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Proje Kapsamı]] + [[Saat Kullanımı]] + [[Brief Onayı]] + [[Teslim Takvimi]] + [[Sözleşme Takibi]] + [[Kaynak Planı]] + [[Teklif Paketi]]…

### Fonksiyonlar
- [[Yarınki yayın sırasını göster]]
- [[Boş yayın slotlarını listele]]
- [[Satılmamış envanteri göster]]
- [[Bu hafta satılan ilanları özetle]]
- [[5651 bilgilendirme eksik mi?]]
- [[İletişim bilgisi güncelliğini kontrol et]]
- [[Yayına denk gelmeyen ilanları bul]]
- [[Çakışan slotları listele]]

### MVP
- [[Proje Kapsamı]]
- [[Saat Kullanımı]]
- [[Brief Onayı]]
- [[Teslim Takvimi]]
- [[Sözleşme Takibi]]
- [[Yayın Masası]]
- [[İlan Envanteri]]
- [[Yasal Bilgi]]

### Sonraki sürüm
- [[Kaynak Planı]]
- [[Teklif Paketi]]
- [[Yayın İlan Eşleme]]

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
- **Değer önerisi (tek cümle):** Kendi mecrasını işleten yayıncı gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
