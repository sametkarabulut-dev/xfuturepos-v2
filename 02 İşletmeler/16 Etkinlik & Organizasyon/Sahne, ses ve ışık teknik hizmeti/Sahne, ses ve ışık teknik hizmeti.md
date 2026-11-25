---
tip: isletme
kod: "16-05-01"
oneri_harf: B
oncelik:
gereksiz: false
oncelik_notu:
sektor: "[[16 Etkinlik & Organizasyon]]"
dal: "[[Dal – Sahne, ses ve ışık teknik hizmeti]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
sayi_turu: tahmin
nace: 90.02
pazar_puani: 3
odeme_puani: 3
rekabet_puani: 3
kolaylik_puani: 4
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
  - "[[Ekipman çıkış]]"
  - "[[Kurulum pencere]]"
  - "[[Dönüş sayım]]"
rakipler:
  - "[[iyzico]]"
  - "[[Biletix / Passo]]"
fonksiyonlar:
  - "[[Muhasebe ve Gelir-Gider]]"
  - "[[e-Fatura ve e-Arşiv]]"
  - "[[CRM]]"
  - "[[Personel ve Vardiya]]"
  - "[[Raporlar]]"
  - "[[AI Asistan]]"
  - "[[Ayarlar]]"
  - "[[Etkinlik takvimi]]"
  - "[[15 Haziran akşam boş mu?]]"
  - "[[Aynı tarihe iki opsiyon var mı?]]"
  - "[[Kapora sözleşme]]"
  - "[[Yılmaz düğününün kaporası geldi mi?]]"
  - "[[Kalan bakiyeyi hatırlat]]"
  - "[[Tedarikçi teyidi]]"
  - "[[Cumartesi ikram teyit etti mi?]]"
  - "[[Teyitsiz tedarikçiler?]]"
  - "[[Run-of-show]]"
  - "[[Akışta 19:00 sonrası ne var?]]"
  - "[[Kurulum penceresi çakışıyor mu?]]"
  - "[[Kişi sayısı]]"
  - "[[Kişi 180'den 220'ye çıktı, ne değişir?]]"
  - "[[Son kişi güncellemesi?]]"
  - "[[Ekipman çıkış]]"
  - "[[2x line array müsait mi?]]"
  - "[[Cumartesi çıkış listesi]]"
  - "[[Kurulum pencere]]"
  - "[[Load-in 14–18 çakışıyor mu?]]"
  - "[[Kaç teknisyen?]]"
  - "[[Dönüş sayım]]"
  - "[[Dönüşte eksik ne?]]"
  - "[[Hasar kaydı aç]]"
parca_sart: 31
parca_olmali: 0
parca_iyi: 0
parca_durum: tamamlandi
---
# 16-05-01 · Sahne, ses ve ışık teknik hizmeti

> Sektör: [[16 Etkinlik & Organizasyon]] · Öncelik: **3.2** / 5 · Öneri: **B**
> Puanlar tahmindir: pazar 3 · ödeme 3 · rekabet boşluğu 3 · kolaylık 4 · aciliyet 3

## 1. Özet
Gösterinin ses, ışık ve sahne tekniğini ekipman ve ekiple kuran firma.

- **İşletme sayısı:** bulunamadı
- **NACE:** 90.02
- **Sayı türü:** tahmin

## 2. Günlük iş akışı
1. Depo çıkışı
2. kurulum penceresi
3. ekip çağrısı
4. söküm
5. dönüş sayımı.

```mermaid
flowchart LR
  S1["Depo çıkışı"] --> S2
  S2["kurulum penceresi"] --> S3
  S3["ekip çağrısı"] --> S4
  S4["söküm"] --> S5
  S5["dönüş sayımı."]
```

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Etkinlik takvimi]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Kapora / sözleşme]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Tedarikçi teyidi]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Run-of-show]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Kişi sayısı]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[e-Belge]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Salon seans]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Telif / MSG listesi]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |

## 4. Parçalar

31 parça · 31 şart · 0 olmalı · 0 iyi olur

### Şart (31)

| Fonksiyon | Araç | Kullanım |
|---|---|---|
| [[Muhasebe ve Gelir-Gider]] | [[Muhasebe ve Gelir-Gider]] | Gelir, gider, cari, kasa ve banka. Sektör belgesi para kaydını buraya düşürür. |
| [[e-Fatura ve e-Arşiv]] | [[e-Fatura ve e-Arşiv]] | Satış belgesi taslağı; gönderim entegratör + onayla. |
| [[CRM]] | [[CRM]] | Kişi/firma kartı, iletişim, not; sektör alanları karta eklenir. |
| [[Personel ve Vardiya]] | [[Personel ve Vardiya]] | Personel kartı, vardiya, puantaj. Bordro/SGK kesilmez. |
| [[Raporlar]] | [[Raporlar]] | Ciro, tahsilat, açık iş ve personel özeti. |
| [[AI Asistan]] | [[AI Asistan]] | Komut çalıştırır, taslak üretir; yüksek etkili işlem onaysız bitmez. |
| [[Ayarlar]] | [[Ayarlar]] | İşletme, belge, bildirim ve entegrasyon ayarları. |
| [[Etkinlik takvimi]] | [[Etkinlik takvimi]] | Tarih/seans/kaynak doluluğu; opsiyon ve kesin kayıt; çakışma engeli. |
| [[15 Haziran akşam boş mu?]] | [[Etkinlik takvimi]] | 15 Haziran akşam boş mu? — Tarih/seans/kaynak doluluğu; opsiyon ve kesin kayıt; çakışma engeli. |
| [[Aynı tarihe iki opsiyon var mı?]] | [[Etkinlik takvimi]] | Aynı tarihe iki opsiyon var mı? — Tarih/seans/kaynak doluluğu; opsiyon ve kesin kayıt; çakışma engeli. |
| [[Kapora sözleşme]] | [[Kapora sözleşme]] | Opsiyon, kapora, kesinleşme, kalan bakiye ve iade kuralı. |
| [[Yılmaz düğününün kaporası geldi mi?]] | [[Kapora sözleşme]] | Yılmaz düğününün kaporası geldi mi? — Opsiyon, kapora, kesinleşme, kalan bakiye ve iade kuralı. |
| [[Kalan bakiyeyi hatırlat]] | [[Kapora sözleşme]] | Kalan bakiyeyi hatırlat — Opsiyon, kapora, kesinleşme, kalan bakiye ve iade kuralı. |
| [[Tedarikçi teyidi]] | [[Tedarikçi teyidi]] | Kalem bazlı tedarikçi atama ve yazılı teyit durumu. |
| [[Cumartesi ikram teyit etti mi?]] | [[Tedarikçi teyidi]] | Cumartesi ikram teyit etti mi? — Kalem bazlı tedarikçi atama ve yazılı teyit durumu. |
| [[Teyitsiz tedarikçiler?]] | [[Tedarikçi teyidi]] | Teyitsiz tedarikçiler? — Kalem bazlı tedarikçi atama ve yazılı teyit durumu. |
| [[Run-of-show]] | [[Run-of-show]] | Etkinlik günü zaman akışı ve bağımlı kalemler. |
| [[Akışta 19:00 sonrası ne var?]] | [[Run-of-show]] | Akışta 19:00 sonrası ne var? — Etkinlik günü zaman akışı ve bağımlı kalemler. |
| [[Kurulum penceresi çakışıyor mu?]] | [[Run-of-show]] | Kurulum penceresi çakışıyor mu? — Etkinlik günü zaman akışı ve bağımlı kalemler. |
| [[Kişi sayısı]] | [[Kişi sayısı]] | Sözleşme kişi sayısı ile güncel sayıyı ve etkileri takip eder. |
| [[Kişi 180'den 220'ye çıktı, ne değişir?]] | [[Kişi sayısı]] | Kişi 180'den 220'ye çıktı, ne değişir? — Sözleşme kişi sayısı ile güncel sayıyı ve etkileri takip eder. |
| [[Son kişi güncellemesi?]] | [[Kişi sayısı]] | Son kişi güncellemesi? — Sözleşme kişi sayısı ile güncel sayıyı ve etkileri takip eder. |
| [[Ekipman çıkış]] | [[Ekipman çıkış]] | Ekipman parkı, işe çıkış fişi ve rezervasyon kilidi. |
| [[2x line array müsait mi?]] | [[Ekipman çıkış]] | 2x line array müsait mi? — Ekipman parkı, işe çıkış fişi ve rezervasyon kilidi. |
| [[Cumartesi çıkış listesi]] | [[Ekipman çıkış]] | Cumartesi çıkış listesi — Ekipman parkı, işe çıkış fişi ve rezervasyon kilidi. |
| [[Kurulum pencere]] | [[Kurulum pencere]] | Load-in/out pencereleri ve ekip çağrısı. |
| [[Load-in 14–18 çakışıyor mu?]] | [[Kurulum pencere]] | Load-in 14–18 çakışıyor mu? — Load-in/out pencereleri ve ekip çağrısı. |
| [[Kaç teknisyen?]] | [[Kurulum pencere]] | Kaç teknisyen? — Load-in/out pencereleri ve ekip çağrısı. |
| [[Dönüş sayım]] | [[Dönüş sayım]] | Çıkış fişi ile dönüş sayımı; eksik/hasar. |
| [[Dönüşte eksik ne?]] | [[Dönüş sayım]] | Dönüşte eksik ne? — Çıkış fişi ile dönüş sayımı; eksik/hasar. |
| [[Hasar kaydı aç]] | [[Dönüş sayım]] | Hasar kaydı aç — Çıkış fişi ile dönüş sayımı; eksik/hasar. |

### Olmalı (0)

_Yok._

### İyi olur (0)

_Yok._

## 5. Teknik detay
- **Entegrasyonlar:** Modül kartlarındaki entegrasyon notlarına bak; açık API yoksa panel kaydı + kullanıcı girişi.
- **Ana ekranlar:** İş listesi / kart · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Rakipler
- [[iyzico]]
- [[Biletix / Passo]]

## 7. Kaynaklar
- [[16 Etkinlik & Organizasyon – Kaynaklar]]
- Araştırma arşivi: `08 Arşiv/eski-docs-sektorel-arastirma/`
