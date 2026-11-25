---
tip: isletme
kod: "09-04-02"
oneri_harf: B
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[09 Emlak & Gayrimenkul]]"
dal: "[[Dal – Turizm amaçlı kısa süreli konut işletmeciliği]]"
durum: tamamlandi
olcek: [mikro, kucuk-orta]
isletme_sayisi: "bulunamadı"
sayi_turu: tahmin
nace: "55.20"
pazar_puani: 2
odeme_puani: 4
rekabet_puani: 3
kolaylik_puani: 3
aciliyet_puani: 4
ihtiyaclar:
  - "[[Yetki belgesi ve sorumlu danışman takibi]]"
  - "[[Portföy kartı ve medya]]"
  - "[[Gösterim randevusu]]"
  - "[[Tahsilat / aidat / komisyon kaydı]]"
  - "[[e-Belge]]"
  - "[[Sözleşme taslağı]]"
  - "[[İlan doğrulama / EİDS checklist]]"
  - "[[Kira tahsilat ve dekont]]"
moduller:
  - "[[Muhasebe ve Gelir-Gider]]"
  - "[[e-Fatura ve e-Arşiv]]"
  - "[[CRM]]"
  - "[[Personel ve Vardiya]]"
  - "[[Raporlar]]"
  - "[[AI Asistan]]"
  - "[[Ayarlar]]"
  - "[[Portföy Kartı]]"
  - "[[Gösterim Randevu]]"
  - "[[İlan Doğrulama]]"
  - "[[Yetki Takibi]]"
  - "[[Sözleşme Taslağı]]"
  - "[[Belge Kasası]]"
  - "[[Komisyon Hesabı]]"
  - "[[Rezervasyon Takvim]]"
  - "[[İzin Belgesi]]"
  - "[[Misafir Checkin]]"
  - "[[Temizlik Planı]]"
  - "[[Kanal Yönetimi]]"
  - "[[Dinamik Fiyat]]"
rakipler:
  - "[[RE-OS]]"
  - "[[selfSite]]"
  - "[[Dijiyon]]"
  - "[[Konsiyon]]"
  - "[[NOKTApp]]"
  - "[[sahibinden]]"
fonksiyonlar:
  - "[[Muhasebe ve Gelir-Gider]]"
  - "[[e-Fatura ve e-Arşiv]]"
  - "[[CRM]]"
  - "[[Personel ve Vardiya]]"
  - "[[Raporlar]]"
  - "[[AI Asistan]]"
  - "[[Ayarlar]]"
  - "[[Portföy Kartı]]"
  - "[[Boşta satılık daireleri listele]]"
  - "[[Kadıköy 3+1 portföyleri getir]]"
  - "[[Gösterim Randevu]]"
  - "[[Yarın 14:00 için gösterim aç]]"
  - "[[Bu hafta müsait slotları göster]]"
  - "[[İlan Doğrulama]]"
  - "[[Bu ilanın EİDS durumunu kontrol et]]"
  - "[[Yetkisiz ilanları işaretle]]"
  - "[[Yetki Takibi]]"
  - "[[Yetki belgesi vadesi yaklaşanları göster]]"
  - "[[Seviye 5 sorumlu listesi]]"
  - "[[Rezervasyon Takvim]]"
  - "[[Bu hafta doluluk göster]]"
  - "[[Çakışan rezervasyonları bul]]"
  - "[[İzin Belgesi]]"
  - "[[İzin belgesi olmayan üniteleri listele]]"
  - "[[Denetim hatırlatmalarını göster]]"
  - "[[Misafir Checkin]]"
  - "[[Bugün check-in listesini getir]]"
  - "[[Eksik kimlik kaydı olanları göster]]"
  - "[[Sözleşme Taslağı]]"
  - "[[Satış yetki sözleşmesi taslağı üret]]"
  - "[[Kira sözleşmesi madde özetini çıkar]]"
  - "[[Belge Kasası]]"
  - "[[Bu portföyün tapu belgelerini listele]]"
  - "[[Süresi dolan belgeleri bul]]"
  - "[[Komisyon Hesabı]]"
  - "[[Bu satışta komisyon tutarını hesapla]]"
  - "[[Danışman payını göster]]"
  - "[[Temizlik Planı]]"
  - "[[Bugünkü temizlik turunu planla]]"
  - "[[Turnover gecikenleri göster]]"
  - "[[Kanal Yönetimi]]"
  - "[[Kanallardaki fiyat farklarını göster]]"
  - "[[Overbooking riskini tara]]"
  - "[[Dinamik Fiyat]]"
  - "[[Yarın için fiyat öner]]"
  - "[[Düşük doluluk günlerini işaretle]]"
parca_sart: 28
parca_olmali: 3
parca_iyi: 15
parca_durum: tamamlandi
---
# 09-04-02 · Yüksek nitelikli konut kısa kiralama yönetimi

> Sektör: [[09 Emlak & Gayrimenkul]] · Öncelik: **3.2** / 5 · Öneri: **B**
> Puanlar tahmindir: pazar 2 · ödeme 4 · rekabet boşluğu 3 · kolaylık 3 · aciliyet 4

## 1. Özet
Yüksek nitelikli konutta yönetim işletmesi; birden fazla ünite, kanal ve temizlik sırası ile kısa kiralama işletir.

- **İşletme sayısı:** bulunamadı
- **NACE:** 55.20
- **Sayı türü:** tahmin

## 2. Günlük iş akışı
1. Ünite / izin
2. Kanal takvim
3. Misafir check-in
4. Turnover temizlik
5. Hasılat özeti

```mermaid
flowchart LR
  S1["Ünite / izin"] --> S2
  S2["Kanal takvim"] --> S3
  S3["Misafir check-in"] --> S4
  S4["Turnover temizlik"] --> S5
  S5["Hasılat özeti"]
```

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Yetki belgesi ve sorumlu danışman takibi]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Portföy kartı ve medya]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Gösterim randevusu]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Tahsilat / aidat / komisyon kaydı]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[e-Belge]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Sözleşme taslağı]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[İlan doğrulama / EİDS checklist]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Kira tahsilat ve dekont]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |

## 4. Parçalar

46 parça · 28 şart · 3 olmalı · 15 iyi olur

### Şart (28)

| Fonksiyon | Araç | Kullanım |
|---|---|---|
| [[Muhasebe ve Gelir-Gider]] | [[Muhasebe ve Gelir-Gider]] | Gelir, gider, cari, kasa ve banka. Sektör belgesi para kaydını buraya düşürür. |
| [[e-Fatura ve e-Arşiv]] | [[e-Fatura ve e-Arşiv]] | Satış belgesi taslağı; gönderim entegratör + onayla. |
| [[CRM]] | [[CRM]] | Kişi/firma kartı, iletişim, not; sektör alanları karta eklenir. |
| [[Personel ve Vardiya]] | [[Personel ve Vardiya]] | Personel kartı, vardiya, puantaj. Bordro/SGK kesilmez. |
| [[Raporlar]] | [[Raporlar]] | Ciro, tahsilat, açık iş ve personel özeti. |
| [[AI Asistan]] | [[AI Asistan]] | Komut çalıştırır, taslak üretir; yüksek etkili işlem onaysız bitmez. |
| [[Ayarlar]] | [[Ayarlar]] | İşletme, belge, bildirim ve entegrasyon ayarları. |
| [[Portföy Kartı]] | [[Portföy Kartı]] | Satış/kira/işletme için taşınmaz kimliği, özellikler, durum ve medya yönetimi. |
| [[Boşta satılık daireleri listele]] | [[Portföy Kartı]] | Boşta satılık daireleri listele — Satış/kira/işletme için taşınmaz kimliği, özellikler, durum ve medya yönetimi. |
| [[Kadıköy 3+1 portföyleri getir]] | [[Portföy Kartı]] | Kadıköy 3+1 portföyleri getir — Satış/kira/işletme için taşınmaz kimliği, özellikler, durum ve medya yönetimi. |
| [[Gösterim Randevu]] | [[Gösterim Randevu]] | Mülk gösterimi randevu, çakışma kontrolü ve danışman ataması. |
| [[Yarın 14:00 için gösterim aç]] | [[Gösterim Randevu]] | Yarın 14:00 için gösterim aç — Mülk gösterimi randevu, çakışma kontrolü ve danışman ataması. |
| [[Bu hafta müsait slotları göster]] | [[Gösterim Randevu]] | Bu hafta müsait slotları göster — Mülk gösterimi randevu, çakışma kontrolü ve danışman ataması. |
| [[İlan Doğrulama]] | [[İlan Doğrulama]] | İlan öncesi kimlik/yetki doğrulama durumu ve yayın checklist'i; EİDS uyumu. |
| [[Bu ilanın EİDS durumunu kontrol et]] | [[İlan Doğrulama]] | Bu ilanın EİDS durumunu kontrol et — İlan öncesi kimlik/yetki doğrulama durumu ve yayın checklist'i; EİDS uyumu. |
| [[Yetkisiz ilanları işaretle]] | [[İlan Doğrulama]] | Yetkisiz ilanları işaretle — İlan öncesi kimlik/yetki doğrulama durumu ve yayın checklist'i; EİDS uyumu. |
| [[Yetki Takibi]] | [[Yetki Takibi]] | İşletme yetki belgesi, sorumlu emlak danışmanı ve belge vade takibi (TTBS). |
| [[Yetki belgesi vadesi yaklaşanları göster]] | [[Yetki Takibi]] | Yetki belgesi vadesi yaklaşanları göster — İşletme yetki belgesi, sorumlu emlak danışmanı ve belge vade takibi (TTBS). |
| [[Seviye 5 sorumlu listesi]] | [[Yetki Takibi]] | Seviye 5 sorumlu listesi — İşletme yetki belgesi, sorumlu emlak danışmanı ve belge vade takibi (TTBS). |
| [[Rezervasyon Takvim]] | [[Rezervasyon Takvim]] | Kısa süreli konaklama takvimi, çakışma ve kapalı gün yönetimi. |
| [[Bu hafta doluluk göster]] | [[Rezervasyon Takvim]] | Bu hafta doluluk göster — Kısa süreli konaklama takvimi, çakışma ve kapalı gün yönetimi. |
| [[Çakışan rezervasyonları bul]] | [[Rezervasyon Takvim]] | Çakışan rezervasyonları bul — Kısa süreli konaklama takvimi, çakışma ve kapalı gün yönetimi. |
| [[İzin Belgesi]] | [[İzin Belgesi]] | e-Devlet izin belgesi numarası, yenileme ve iptal risk takibi. |
| [[İzin belgesi olmayan üniteleri listele]] | [[İzin Belgesi]] | İzin belgesi olmayan üniteleri listele — e-Devlet izin belgesi numarası, yenileme ve iptal risk takibi. |
| [[Denetim hatırlatmalarını göster]] | [[İzin Belgesi]] | Denetim hatırlatmalarını göster — e-Devlet izin belgesi numarası, yenileme ve iptal risk takibi. |
| [[Misafir Checkin]] | [[Misafir Checkin]] | Kimlik/pasaport kaydı, giriş-çıkış ve ev kuralları onayı. |
| [[Bugün check-in listesini getir]] | [[Misafir Checkin]] | Bugün check-in listesini getir — Kimlik/pasaport kaydı, giriş-çıkış ve ev kuralları onayı. |
| [[Eksik kimlik kaydı olanları göster]] | [[Misafir Checkin]] | Eksik kimlik kaydı olanları göster — Kimlik/pasaport kaydı, giriş-çıkış ve ev kuralları onayı. |

### Olmalı (3)

| Fonksiyon | Araç | Kullanım |
|---|---|---|
| [[Sözleşme Taslağı]] | [[Sözleşme Taslağı]] | Satış/kira/yetkilendirme taslak üretimi; imza ve gönderim insan onayına bağlı. |
| [[Satış yetki sözleşmesi taslağı üret]] | [[Sözleşme Taslağı]] | Satış yetki sözleşmesi taslağı üret — Satış/kira/yetkilendirme taslak üretimi; imza ve gönderim insan onayına bağlı. |
| [[Kira sözleşmesi madde özetini çıkar]] | [[Sözleşme Taslağı]] | Kira sözleşmesi madde özetini çıkar — Satış/kira/yetkilendirme taslak üretimi; imza ve gönderim insan onayına bağlı. |

### İyi olur (15)

| Fonksiyon | Araç | Kullanım |
|---|---|---|
| [[Belge Kasası]] | [[Belge Kasası]] | Tapu, kimlik, yetki ve ekspertiz belgelerinin versiyonlu arşivi. |
| [[Bu portföyün tapu belgelerini listele]] | [[Belge Kasası]] | Bu portföyün tapu belgelerini listele — Tapu, kimlik, yetki ve ekspertiz belgelerinin versiyonlu arşivi. |
| [[Süresi dolan belgeleri bul]] | [[Belge Kasası]] | Süresi dolan belgeleri bul — Tapu, kimlik, yetki ve ekspertiz belgelerinin versiyonlu arşivi. |
| [[Komisyon Hesabı]] | [[Komisyon Hesabı]] | Muhasebe & Gelir-Gider genişlemesi: işlem komisyonu ve ofis/danışman payı önerisi. |
| [[Bu satışta komisyon tutarını hesapla]] | [[Komisyon Hesabı]] | Bu satışta komisyon tutarını hesapla — Muhasebe & Gelir-Gider genişlemesi: işlem komisyonu ve ofis/danışman payı önerisi. |
| [[Danışman payını göster]] | [[Komisyon Hesabı]] | Danışman payını göster — Muhasebe & Gelir-Gider genişlemesi: işlem komisyonu ve ofis/danışman payı önerisi. |
| [[Temizlik Planı]] | [[Temizlik Planı]] | Personel & Vardiya genişlemesi: çıkış sonrası temizlik ve turnover planı. |
| [[Bugünkü temizlik turunu planla]] | [[Temizlik Planı]] | Bugünkü temizlik turunu planla — Personel & Vardiya genişlemesi: çıkış sonrası temizlik ve turnover planı. |
| [[Turnover gecikenleri göster]] | [[Temizlik Planı]] | Turnover gecikenleri göster — Personel & Vardiya genişlemesi: çıkış sonrası temizlik ve turnover planı. |
| [[Kanal Yönetimi]] | [[Kanal Yönetimi]] | OTA/ilan kanallarında takvim/fiyat senkron uyumsuzluk takibi. |
| [[Kanallardaki fiyat farklarını göster]] | [[Kanal Yönetimi]] | Kanallardaki fiyat farklarını göster — OTA/ilan kanallarında takvim/fiyat senkron uyumsuzluk takibi. |
| [[Overbooking riskini tara]] | [[Kanal Yönetimi]] | Overbooking riskini tara — OTA/ilan kanallarında takvim/fiyat senkron uyumsuzluk takibi. |
| [[Dinamik Fiyat]] | [[Dinamik Fiyat]] | Sezon ve doluluk bazlı fiyat bandı önerisi; yazma insan onaylı. |
| [[Yarın için fiyat öner]] | [[Dinamik Fiyat]] | Yarın için fiyat öner — Sezon ve doluluk bazlı fiyat bandı önerisi; yazma insan onaylı. |
| [[Düşük doluluk günlerini işaretle]] | [[Dinamik Fiyat]] | Düşük doluluk günlerini işaretle — Sezon ve doluluk bazlı fiyat bandı önerisi; yazma insan onaylı. |

## 5. Teknik detay
- **Entegrasyonlar:** Modül kartlarına bak; açık API yoksa panel kaydı.
- **Ana ekranlar:** İş listesi · Kart · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay)`

## 6. Rakipler
- [[RE-OS]]
- [[selfSite]]
- [[Dijiyon]]
- [[Konsiyon]]
- [[NOKTApp]]
- [[sahibinden]]

## 7. Kaynaklar
- [[09 Emlak & Gayrimenkul – Kaynaklar]]
