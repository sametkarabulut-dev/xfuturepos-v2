---
tip: isletme
kod: "16-02-01"
oneri_harf: B
oncelik:
gereksiz: false
oncelik_notu:
sektor: "[[16 Etkinlik & Organizasyon]]"
dal: "[[Dal – Etkinlik ikramı]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
sayi_turu: tahmin
nace: 56.21
pazar_puani: 3
odeme_puani: 3
rekabet_puani: 3
kolaylik_puani: 3
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
  - "[[Menü maliyet]]"
  - "[[Üretim sevkiyat]]"
  - "[[Gıda kayıt]]"
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
  - "[[Menü maliyet]]"
  - "[[220 kişilik menü maliyeti?]]"
  - "[[Vejetaryen 30 kişi ekle]]"
  - "[[Üretim sevkiyat]]"
  - "[[Cumartesi üretim planı]]"
  - "[[Kap-kacak döndü mü?]]"
  - "[[Gıda kayıt]]"
  - "[[Gıda kayıt numarası?]]"
  - "[[Belge adresi değişti mi?]]"
parca_sart: 31
parca_olmali: 0
parca_iyi: 0
parca_durum: tamamlandi
---
# 16-02-01 · Etkinlik ikramı

> Sektör: [[16 Etkinlik & Organizasyon]] · Öncelik: **3.0** / 5 · Öneri: **B**
> Puanlar tahmindir: pazar 3 · ödeme 3 · rekabet boşluğu 3 · kolaylık 3 · aciliyet 3

## 1. Özet
Müşterinin belirlediği etkinlikte sözleşmeyle yemek üreten işletme. Lokanta ve tabldot burada değildir.

- **İşletme sayısı:** bulunamadı
- **NACE:** 56.21
- **Sayı türü:** tahmin

## 2. Günlük iş akışı
1. Tarih
2. kişi sayısı
3. menü maliyeti
4. üretim
5. taşıma
6. servis ekibi
7. kap dönüşü.

```mermaid
flowchart LR
  S1["Tarih"] --> S2
  S2["kişi sayısı"] --> S3
  S3["menü maliyeti"] --> S4
  S4["üretim"] --> S5
  S5["taşıma"] --> S6
  S6["servis ekibi"] --> S7
  S7["kap dönüşü."]
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
| [[Menü maliyet]] | [[Menü maliyet]] | Reçete, kişi başı maliyet ve teklif. |
| [[220 kişilik menü maliyeti?]] | [[Menü maliyet]] | 220 kişilik menü maliyeti? — Reçete, kişi başı maliyet ve teklif. |
| [[Vejetaryen 30 kişi ekle]] | [[Menü maliyet]] | Vejetaryen 30 kişi ekle — Reçete, kişi başı maliyet ve teklif. |
| [[Üretim sevkiyat]] | [[Üretim sevkiyat]] | Mutfak planı, taşıma, servis ekibi, kap-kacak dönüşü. |
| [[Cumartesi üretim planı]] | [[Üretim sevkiyat]] | Cumartesi üretim planı — Mutfak planı, taşıma, servis ekibi, kap-kacak dönüşü. |
| [[Kap-kacak döndü mü?]] | [[Üretim sevkiyat]] | Kap-kacak döndü mü? — Mutfak planı, taşıma, servis ekibi, kap-kacak dönüşü. |
| [[Gıda kayıt]] | [[Gıda kayıt]] | İşletme kayıt belgesi ve faaliyet konusu dosyası. |
| [[Gıda kayıt numarası?]] | [[Gıda kayıt]] | Gıda kayıt numarası? — İşletme kayıt belgesi ve faaliyet konusu dosyası. |
| [[Belge adresi değişti mi?]] | [[Gıda kayıt]] | Belge adresi değişti mi? — İşletme kayıt belgesi ve faaliyet konusu dosyası. |

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
