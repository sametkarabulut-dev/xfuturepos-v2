---
tip: isletme
kod: "09-05-01"
oneri_harf: A
oncelik:
gereksiz: false
oncelik_notu: ""
sektor: "[[09 Emlak & Gayrimenkul]]"
dal: "[[Dal – Uzun süreli kira ve mülk işletmeciliği]]"
durum: tamamlandi
olcek: [mikro, kucuk-orta]
isletme_sayisi: "İTO 68.32.02: 795 (ücretli yönetim kümesi; kırılım bulunamadı)"
sayi_turu: tahmin
nace: "68.32"
pazar_puani: 3
odeme_puani: 4
rekabet_puani: 3
kolaylik_puani: 4
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
  - "[[Kira Dosyası]]"
  - "[[Kira Tahsilat]]"
  - "[[Bakım İş Emri]]"
  - "[[Tahliye Takvimi]]"
  - "[[Depozito Defteri]]"
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
  - "[[Kira Dosyası]]"
  - "[[Bitimine 60 gün kalan kiraları listele]]"
  - "[[Bu sözleşmenin artış maddesini özetle]]"
  - "[[Kira Tahsilat]]"
  - "[[Bu ay ödenmeyen kiraları getir]]"
  - "[[Gecikme tutarını hesapla]]"
  - "[[Bakım İş Emri]]"
  - "[[Açık arızaları önceliklendir]]"
  - "[[Bu ay bakım maliyetini özetle]]"
  - "[[Sözleşme Taslağı]]"
  - "[[Satış yetki sözleşmesi taslağı üret]]"
  - "[[Kira sözleşmesi madde özetini çıkar]]"
  - "[[Belge Kasası]]"
  - "[[Bu portföyün tapu belgelerini listele]]"
  - "[[Süresi dolan belgeleri bul]]"
  - "[[Komisyon Hesabı]]"
  - "[[Bu satışta komisyon tutarını hesapla]]"
  - "[[Danışman payını göster]]"
  - "[[Tahliye Takvimi]]"
  - "[[Tahliye tarihi yaklaşanları göster]]"
  - "[[TBK 352 sürelerini kontrol et]]"
  - "[[Depozito Defteri]]"
  - "[[İade bekleyen depozitoları listele]]"
  - "[[Mahsup kalemlerini özetle]]"
parca_sart: 28
parca_olmali: 3
parca_iyi: 12
parca_durum: tamamlandi
---
# 09-05-01 · Başkası adına kira yöneticisi

> Sektör: [[09 Emlak & Gayrimenkul]] · Öncelik: **3.6** / 5 · Öneri: **A**
> Puanlar tahmindir: pazar 3 · ödeme 4 · rekabet boşluğu 3 · kolaylık 4 · aciliyet 4

## 1. Özet
Sözleşmeyle malik adına uzun kira tahsilatı, boşalma ve bakım işletir; malike dönem hesabı verir.

- **İşletme sayısı:** İTO 68.32.02: 795 (ücretli yönetim kümesi; kırılım bulunamadı)
- **NACE:** 68.32
- **Sayı türü:** tahmin

## 2. Günlük iş akışı
1. Malik yetkisi
2. Kiracı dosyası
3. Tahsilat / dekont
4. Arıza iş emri
5. Malik özeti

```mermaid
flowchart LR
  S1["Malik yetkisi"] --> S2
  S2["Kiracı dosyası"] --> S3
  S3["Tahsilat / dekont"] --> S4
  S4["Arıza iş emri"] --> S5
  S5["Malik özeti"]
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
| [[Kira Dosyası]] | [[Kira Dosyası]] | Kira sözleşmesi, süre, artış ve eklerin dosya bazlı yönetimi. |
| [[Bitimine 60 gün kalan kiraları listele]] | [[Kira Dosyası]] | Bitimine 60 gün kalan kiraları listele — Kira sözleşmesi, süre, artış ve eklerin dosya bazlı yönetimi. |
| [[Bu sözleşmenin artış maddesini özetle]] | [[Kira Dosyası]] | Bu sözleşmenin artış maddesini özetle — Kira sözleşmesi, süre, artış ve eklerin dosya bazlı yönetimi. |
| [[Kira Tahsilat]] | [[Kira Tahsilat]] | Muhasebe & Gelir-Gider genişlemesi: kira vade, gecikme ve dekont eşlemesi. |
| [[Bu ay ödenmeyen kiraları getir]] | [[Kira Tahsilat]] | Bu ay ödenmeyen kiraları getir — Muhasebe & Gelir-Gider genişlemesi: kira vade, gecikme ve dekont eşlemesi. |
| [[Gecikme tutarını hesapla]] | [[Kira Tahsilat]] | Gecikme tutarını hesapla — Muhasebe & Gelir-Gider genişlemesi: kira vade, gecikme ve dekont eşlemesi. |
| [[Bakım İş Emri]] | [[Bakım İş Emri]] | Kiracı/malik arıza kaydı, tedarikçi atama ve kapanış. |
| [[Açık arızaları önceliklendir]] | [[Bakım İş Emri]] | Açık arızaları önceliklendir — Kiracı/malik arıza kaydı, tedarikçi atama ve kapanış. |
| [[Bu ay bakım maliyetini özetle]] | [[Bakım İş Emri]] | Bu ay bakım maliyetini özetle — Kiracı/malik arıza kaydı, tedarikçi atama ve kapanış. |

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
| [[Tahliye Takvimi]] | [[Tahliye Takvimi]] | Tahliye taahhüdü tarihleri ve yasal süre hatırlatmaları. |
| [[Tahliye tarihi yaklaşanları göster]] | [[Tahliye Takvimi]] | Tahliye tarihi yaklaşanları göster — Tahliye taahhüdü tarihleri ve yasal süre hatırlatmaları. |
| [[TBK 352 sürelerini kontrol et]] | [[Tahliye Takvimi]] | TBK 352 sürelerini kontrol et — Tahliye taahhüdü tarihleri ve yasal süre hatırlatmaları. |
| [[Depozito Defteri]] | [[Depozito Defteri]] | Depozito alma, iade, mahsup ve belgelendirme. |
| [[İade bekleyen depozitoları listele]] | [[Depozito Defteri]] | İade bekleyen depozitoları listele — Depozito alma, iade, mahsup ve belgelendirme. |
| [[Mahsup kalemlerini özetle]] | [[Depozito Defteri]] | Mahsup kalemlerini özetle — Depozito alma, iade, mahsup ve belgelendirme. |

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
