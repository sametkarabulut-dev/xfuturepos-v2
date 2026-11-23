---
tip: isletme
kod: "15-07-01"
oneri_harf: B
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[15 Teknoloji Medya & Ajans]]"
dal: "[[Dal – BT bakım ve paket yazılım destek ofisi]]"
durum: tamamlandi
olcek: ['tek-kisilik', 'mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
nace: "62.02"
pazar_puani: 3
odeme_puani: 4
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
  - "[[SLA Ticket]]"
  - "[[Kurulum Kaydı]]"
  - "[[Destek Sözleşmesi]]"
  - "[[Lisans Takibi]]"
  - "[[Uzaktan Bağlantı]]"
rakipler:
  - "[[Meta Ads]]"
  - "[[Google Ads]]"
  - "[[GitHub / GitLab]]"
fonksiyonlar:
  - "[[SLA'sı dolmak üzere ticket'ları göster]]"
  - "[[Eksik bilgili talepleri ayıkla]]"
  - "[[Kurulum checklist'i çıkar]]"
  - "[[Eğitimi tamamlanmayanları listele]]"
  - "[[Biten destek sözleşmelerini göster]]"
  - "[[Yenileme hatırlatması hazırla]]"
  - "[[Lisansı biten müşterileri listele]]"
  - "[[Lisans durumunu özetle]]"
  - "[[Açık uzaktan erişimleri listele]]"
  - "[[Oturum notunu özetle]]"
fiyat_araligi: "bulunamadı"
is_modeli: "Abonelik (tahmin) — karma"
---
# 15-07-01 · BT bakım ve paket yazılım destek ofisi

> Sektör: [[15 Teknoloji Medya & Ajans]] · Öncelik: **3.4** / 5 · Öneri: **B**
> Puanlar tahmindir: pazar 3 · ödeme 4 · rekabet boşluğu 3 · kolaylık 4 · aciliyet 3

## 1. Özet
Başkasının paket yazılımını kuran, eğiten ve arıza kuyruğu yürüten ofis. Ticari barındırma aynı kuyruksa buradadır.

- **İşletme sayısı:** bulunamadı
- **NACE:** 62.02

## 2. Günlük iş akışı
1. Kurulum
2. eğitim
3. talep
4. sözleşme süresi.

```mermaid
flowchart LR
  S1["Kurulum"] --> S2
  S2["eğitim"] --> S3
  S3["talep"] --> S4
  S4["sözleşme süresi."]
```

AI destek (onaylı): Talep metninden eksik bilgiyi ve süre riskini not eder.

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Proje Kapsamı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Saat Kullanımı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Brief Onayı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[SLA Ticket]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Kurulum Kaydı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Destek Sözleşmesi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Lisans Takibi]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |
| [[Uzaktan Bağlantı]] | Excel / WhatsApp / portal (tahmin) | Zaman kaybı, hata riski |

## 4. Çözümümüz: modüller ve özellikler
**Araç tarifi:** [[Muhasebe ve Gelir-Gider]] + [[e-Fatura ve e-Arşiv]] + [[CRM]] + [[Personel ve Vardiya]] + [[Raporlar]] + [[AI Asistan]] + [[Ayarlar]] + [[Proje Kapsamı]] + [[Saat Kullanımı]] + [[Brief Onayı]] + [[Teslim Takvimi]] + [[Sözleşme Takibi]] + [[Kaynak Planı]] + [[Teklif Paketi]]…

### Fonksiyonlar
- [[SLA'sı dolmak üzere ticket'ları göster]]
- [[Eksik bilgili talepleri ayıkla]]
- [[Kurulum checklist'i çıkar]]
- [[Eğitimi tamamlanmayanları listele]]
- [[Biten destek sözleşmelerini göster]]
- [[Yenileme hatırlatması hazırla]]
- [[Lisansı biten müşterileri listele]]
- [[Lisans durumunu özetle]]
- [[Açık uzaktan erişimleri listele]]
- [[Oturum notunu özetle]]

### MVP
- [[Proje Kapsamı]]
- [[Saat Kullanımı]]
- [[Brief Onayı]]
- [[Teslim Takvimi]]
- [[Sözleşme Takibi]]
- [[SLA Ticket]]
- [[Kurulum Kaydı]]
- [[Destek Sözleşmesi]]

### Sonraki sürüm
- [[Kaynak Planı]]
- [[Teklif Paketi]]
- [[Lisans Takibi]]
- [[Uzaktan Bağlantı]]

## 5. Teknik detay
- **Entegrasyonlar:** Elle lisans tarihi
- **Ana ekranlar:** Kart / iş listesi · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Fiyat ve paket önerisi
| Paket | İçerik | Fiyat | Not |
|---|---|---|---|
| Başlangıç | Çekirdek + MVP araçlar | bulunamadı | tahmin |
| Plus | V2 araçlar | bulunamadı | tahmin |

Uygun iş modeli: Abonelik (taahhütsüz aylık; yıllık indirim) — tahmin

## 7. Satış argümanı
- **Değer önerisi (tek cümle):** BT bakım ve paket yazılım destek ofisi gününü tek panelde toplar; resmi gönderim ve tahsilat onayda kalır.
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
