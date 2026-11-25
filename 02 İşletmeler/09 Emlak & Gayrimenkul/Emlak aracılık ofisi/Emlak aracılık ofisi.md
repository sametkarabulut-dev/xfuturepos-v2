---
tip: isletme
kod: "09-01-01"
oneri_harf: A
oncelik:
gereksiz: false
oncelik_notu:
sektor: "[[09 Emlak & Gayrimenkul]]"
dal: "[[Dal – Emlak aracılık ofisi]]"
durum: tamamlandi
olcek: ['tek-kisilik', 'mikro', 'kucuk-orta']
isletme_sayisi: "İTO 68.31.01: 14.828 (İstanbul oda; TR geneli yok)"
isletme_sayisi_n: 14828
sayi_turu: kaynakli
nace: 68.31
pazar_puani: 5
odeme_puani: 4
rekabet_puani: 2
kolaylik_puani: 3
aciliyet_puani: 5
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
  - "[[Alıcı Eşleştirme]]"
  - "[[Malik Yetkilendirme]]"
  - "[[Teklif Takibi]]"
  - "[[Ofis Portföy Payı]]"
  - "[[Piyasa Bandı]]"
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
  - "[[Sözleşme Taslağı]]"
  - "[[Satış yetki sözleşmesi taslağı üret]]"
  - "[[Kira sözleşmesi madde özetini çıkar]]"
  - "[[Belge Kasası]]"
  - "[[Bu portföyün tapu belgelerini listele]]"
  - "[[Süresi dolan belgeleri bul]]"
  - "[[Komisyon Hesabı]]"
  - "[[Bu satışta komisyon tutarını hesapla]]"
  - "[[Danışman payını göster]]"
  - "[[Alıcı Eşleştirme]]"
  - "[[Bu alıcıya 5 aday öner]]"
  - "[[Bütçe 8–10M eşleşmeleri getir]]"
  - "[[Malik Yetkilendirme]]"
  - "[[Yetki bekleyen portföyleri göster]]"
  - "[[Yetki kodu süresi dolanları listele]]"
  - "[[Teklif Takibi]]"
  - "[[Açık teklifleri sırala]]"
  - "[[Bu portföyün son teklifini özetle]]"
  - "[[Ofis Portföy Payı]]"
  - "[[Ortak portföyleri listele]]"
  - "[[Paylaşım kuralını özetle]]"
  - "[[Piyasa Bandı]]"
  - "[[Bu daire için fiyat bandı öner]]"
  - "[[Son 30 gün benzer satılıkları özetle]]"
parca_sart: 28
parca_olmali: 3
parca_iyi: 12
parca_durum: tamamlandi
---
# 09-01-01 · Emlak aracılık ofisi

> Sektör: [[09 Emlak & Gayrimenkul]] · Öncelik: **3.8** / 5 · Öneri: **A**
> Puanlar tahmindir: pazar 5 · ödeme 4 · rekabet boşluğu 2 · kolaylık 3 · aciliyet 5

## 1. Özet
Yetki belgeli işletme, başkasına ait konut, işyeri, arsa veya devre mülke komisyonla aracılık eder.

- **İşletme sayısı:** İTO 68.31.01: 14.828 (İstanbul oda; TR geneli yok)
- **NACE:** 68.31
- **Sayı türü:** kaynakli

## 2. Günlük iş akışı
1. Yetkilendirme dosyası
2. EİDS izinli ilan
3. talep eşleme
4. yer gösterme
5. yazılı teklif
6. aracılık sözleşmesi.

```mermaid
flowchart LR
  S1["Yetkilendirme dosyası"] --> S2
  S2["EİDS izinli ilan"] --> S3
  S3["talep eşleme"] --> S4
  S4["yer gösterme"] --> S5
  S5["yazılı teklif"] --> S6
  S6["aracılık sözleşmesi."]
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

43 parça · 28 şart · 3 olmalı · 12 iyi olur

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
| [[Alıcı Eşleştirme]] | [[Alıcı Eşleştirme]] | CRM genişlemesi: bütçe/lokasyon/özellik ile portföy adayı skorlama. |
| [[Bu alıcıya 5 aday öner]] | [[Alıcı Eşleştirme]] | Bu alıcıya 5 aday öner — CRM genişlemesi: bütçe/lokasyon/özellik ile portföy adayı skorlama. |
| [[Bütçe 8–10M eşleşmeleri getir]] | [[Alıcı Eşleştirme]] | Bütçe 8–10M eşleşmeleri getir — CRM genişlemesi: bütçe/lokasyon/özellik ile portföy adayı skorlama. |
| [[Malik Yetkilendirme]] | [[Malik Yetkilendirme]] | Malikin e-Devlet üzerinden emlak işletmesine verdiği ilan yetkisinin takip kaydı. |
| [[Yetki bekleyen portföyleri göster]] | [[Malik Yetkilendirme]] | Yetki bekleyen portföyleri göster — Malikin e-Devlet üzerinden emlak işletmesine verdiği ilan yetkisinin takip kaydı. |
| [[Yetki kodu süresi dolanları listele]] | [[Malik Yetkilendirme]] | Yetki kodu süresi dolanları listele — Malikin e-Devlet üzerinden emlak işletmesine verdiği ilan yetkisinin takip kaydı. |
| [[Teklif Takibi]] | [[Teklif Takibi]] | Alıcı teklifleri, karşı teklif ve durum pipeline'ı. |
| [[Açık teklifleri sırala]] | [[Teklif Takibi]] | Açık teklifleri sırala — Alıcı teklifleri, karşı teklif ve durum pipeline'ı. |
| [[Bu portföyün son teklifini özetle]] | [[Teklif Takibi]] | Bu portföyün son teklifini özetle — Alıcı teklifleri, karşı teklif ve durum pipeline'ı. |

### Olmalı (3)

| Fonksiyon | Araç | Kullanım |
|---|---|---|
| [[Sözleşme Taslağı]] | [[Sözleşme Taslağı]] | Satış/kira/yetkilendirme taslak üretimi; imza ve gönderim insan onayına bağlı. |
| [[Satış yetki sözleşmesi taslağı üret]] | [[Sözleşme Taslağı]] | Satış yetki sözleşmesi taslağı üret — Satış/kira/yetkilendirme taslak üretimi; imza ve gönderim insan onayına bağlı. |
| [[Kira sözleşmesi madde özetini çıkar]] | [[Sözleşme Taslağı]] | Kira sözleşmesi madde özetini çıkar — Satış/kira/yetkilendirme taslak üretimi; imza ve gönderim insan onayına bağlı. |

### İyi olur (12)

| Fonksiyon | Araç | Kullanım |
|---|---|---|
| [[Belge Kasası]] | [[Belge Kasası]] | Tapu, kimlik, yetki ve ekspertiz belgelerinin versiyonlu arşivi. |
| [[Bu portföyün tapu belgelerini listele]] | [[Belge Kasası]] | Bu portföyün tapu belgelerini listele — Tapu, kimlik, yetki ve ekspertiz belgelerinin versiyonlu arşivi. |
| [[Süresi dolan belgeleri bul]] | [[Belge Kasası]] | Süresi dolan belgeleri bul — Tapu, kimlik, yetki ve ekspertiz belgelerinin versiyonlu arşivi. |
| [[Komisyon Hesabı]] | [[Komisyon Hesabı]] | Muhasebe & Gelir-Gider genişlemesi: işlem komisyonu ve ofis/danışman payı önerisi. |
| [[Bu satışta komisyon tutarını hesapla]] | [[Komisyon Hesabı]] | Bu satışta komisyon tutarını hesapla — Muhasebe & Gelir-Gider genişlemesi: işlem komisyonu ve ofis/danışman payı önerisi. |
| [[Danışman payını göster]] | [[Komisyon Hesabı]] | Danışman payını göster — Muhasebe & Gelir-Gider genişlemesi: işlem komisyonu ve ofis/danışman payı önerisi. |
| [[Ofis Portföy Payı]] | [[Ofis Portföy Payı]] | Şube/franchise arası portföy görünürlük ve komisyon paylaşım kuralları. |
| [[Ortak portföyleri listele]] | [[Ofis Portföy Payı]] | Ortak portföyleri listele — Şube/franchise arası portföy görünürlük ve komisyon paylaşım kuralları. |
| [[Paylaşım kuralını özetle]] | [[Ofis Portföy Payı]] | Paylaşım kuralını özetle — Şube/franchise arası portföy görünürlük ve komisyon paylaşım kuralları. |
| [[Piyasa Bandı]] | [[Piyasa Bandı]] | Benzer ilanlardan bilgilendirme amaçlı fiyat bandı önerisi. |
| [[Bu daire için fiyat bandı öner]] | [[Piyasa Bandı]] | Bu daire için fiyat bandı öner — Benzer ilanlardan bilgilendirme amaçlı fiyat bandı önerisi. |
| [[Son 30 gün benzer satılıkları özetle]] | [[Piyasa Bandı]] | Son 30 gün benzer satılıkları özetle — Benzer ilanlardan bilgilendirme amaçlı fiyat bandı önerisi. |

## 5. Teknik detay
- **Entegrasyonlar:** Modül kartlarındaki entegrasyon notlarına bak; açık API yoksa panel kaydı + kullanıcı girişi.
- **Ana ekranlar:** İş listesi / kart · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Rakipler
- [[RE-OS]]
- [[selfSite]]
- [[Dijiyon]]
- [[Konsiyon]]
- [[NOKTApp]]
- [[sahibinden]]

## 7. Kaynaklar
- [[09 Emlak & Gayrimenkul – Kaynaklar]]
- Araştırma arşivi: `08 Arşiv/eski-docs-sektorel-arastirma/`
