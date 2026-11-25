---
tip: isletme
kod: "10-05-01"
oneri_harf: B
oncelik:
gereksiz: false
oncelik_notu:
sektor: "[[10 İnşaat & Yapı]]"
dal: "[[Dal – Yapı malzemesi bayii]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
sayi_turu: tahmin
nace: 46.83
pazar_puani: 3
odeme_puani: 4
rekabet_puani: 2
kolaylik_puani: 3
aciliyet_puani: 3
ihtiyaclar:
  - "[[Proje / iş kartı]]"
  - "[[Puantaj / yoklama]]"
  - "[[Metraj ve hakediş]]"
  - "[[Malzeme / stok]]"
  - "[[e-Belge]]"
  - "[[Şantiye günlüğü]]"
  - "[[Ruhsat / evrak paketi]]"
  - "[[İSG checklist]]"
moduller:
  - "[[Muhasebe ve Gelir-Gider]]"
  - "[[e-Fatura ve e-Arşiv]]"
  - "[[CRM]]"
  - "[[Personel ve Vardiya]]"
  - "[[Raporlar]]"
  - "[[AI Asistan]]"
  - "[[Ayarlar]]"
  - "[[Proje Kartı]]"
  - "[[Saha Puantajı]]"
  - "[[Metraj Hakediş]]"
  - "[[Şantiye Günlüğü]]"
  - "[[Malzeme Takibi]]"
  - "[[İSG Kontrol]]"
  - "[[Taşeron Sözleşme]]"
  - "[[Sipariş Stok]]"
  - "[[Sevkiyat İrsaliye]]"
  - "[[Şantiye Teslim]]"
  - "[[Fiyat Liste]]"
  - "[[Cari Limit]]"
rakipler:
  - "[[SantiyePro]]"
  - "[[Hakedra]]"
  - "[[ESSantiye]]"
  - "[[Mikro]]"
fonksiyonlar:
  - "[[Muhasebe ve Gelir-Gider]]"
  - "[[e-Fatura ve e-Arşiv]]"
  - "[[CRM]]"
  - "[[Personel ve Vardiya]]"
  - "[[Raporlar]]"
  - "[[AI Asistan]]"
  - "[[Ayarlar]]"
  - "[[Proje Kartı]]"
  - "[[Aktif şantiyeleri listele]]"
  - "[[C blok projesini askıya al]]"
  - "[[Saha Puantajı]]"
  - "[[Bugün B blokta kaç kişi var?]]"
  - "[[Elektrik ekibi puantajını özetle]]"
  - "[[Metraj Hakediş]]"
  - "[[Mart hakediş taslağını hazırla]]"
  - "[[Kalıp m² farkını göster]]"
  - "[[Şantiye Günlüğü]]"
  - "[[Bugünkü günlük raporu hazırla]]"
  - "[[Son 7 gün çalışılmayan günleri göster]]"
  - "[[Malzeme Takibi]]"
  - "[[Bugün gelen demiri kaydet]]"
  - "[[Beton sarfiyatı metrajı aşıyor mu?]]"
  - "[[İSG Kontrol]]"
  - "[[Süresi dolan İSG belgelerini listele]]"
  - "[[Ramak kala aç]]"
  - "[[Taşeron Sözleşme]]"
  - "[[Yeni sıva taşeron sözleşmesi oluştur]]"
  - "[[Ek iş protokollerini göster]]"
  - "[[Sipariş Stok]]"
  - "[[Çimento stoğunu söyle]]"
  - "[[X şantiyesi için 20 ton ayır]]"
  - "[[Sevkiyat İrsaliye]]"
  - "[[Yarınki sevkiyatları listele]]"
  - "[[e-İrsaliye kes]]"
  - "[[Şantiye Teslim]]"
  - "[[Reddedilen sevkiyatları göster]]"
  - "[[Kısmi kabul kaydet]]"
  - "[[Fiyat Liste]]"
  - "[[Demir fiyatını güncelle]]"
  - "[[A carisine özel liste]]"
  - "[[Cari Limit]]"
  - "[[Limit aşan carileri göster]]"
  - "[[B carisine limit koy]]"
parca_sart: 31
parca_olmali: 0
parca_iyi: 12
parca_durum: tamamlandi
---
# 10-05-01 · Yapı malzemesi bayii

> Sektör: [[10 İnşaat & Yapı]] · Öncelik: **3.0** / 5 · Öneri: **B**
> Puanlar tahmindir: pazar 3 · ödeme 4 · rekabet boşluğu 2 · kolaylık 3 · aciliyet 3

## 1. Özet
Çimento, tuğla, seramik, doğrama veya sıhhi malzeme stoklayıp şantiyeye vadeli satan toptancı.

- **İşletme sayısı:** bulunamadı
- **NACE:** 46.83
- **Sayı türü:** tahmin

## 2. Günlük iş akışı
1. Stok
2. fiyat
3. sipariş
4. şantiye teslimatı
5. cari risk
6. irsaliye.

```mermaid
flowchart LR
  S1["Stok"] --> S2
  S2["fiyat"] --> S3
  S3["sipariş"] --> S4
  S4["şantiye teslimatı"] --> S5
  S5["cari risk"] --> S6
  S6["irsaliye."]
```

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Proje / iş kartı]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Puantaj / yoklama]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Metraj ve hakediş]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Malzeme / stok]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[e-Belge]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Şantiye günlüğü]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Ruhsat / evrak paketi]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[İSG checklist]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |

## 4. Parçalar

43 parça · 31 şart · 0 olmalı · 12 iyi olur

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
| [[Proje Kartı]] | [[Proje Kartı]] | Şantiye/iş kartı; CRM genişlemesi. |
| [[Aktif şantiyeleri listele]] | [[Proje Kartı]] | Aktif şantiyeleri listele — Şantiye/iş kartı; CRM genişlemesi. |
| [[C blok projesini askıya al]] | [[Proje Kartı]] | C blok projesini askıya al — Şantiye/iş kartı; CRM genişlemesi. |
| [[Saha Puantajı]] | [[Saha Puantajı]] | Firma-ekip-blok puantaj; Personel genişlemesi. Çekirdek genişleme: Personel & Vardiya. |
| [[Bugün B blokta kaç kişi var?]] | [[Saha Puantajı]] | Bugün B blokta kaç kişi var? — Firma-ekip-blok puantaj; Personel genişlemesi. Çekirdek genişleme: Personel & Vardiya. |
| [[Elektrik ekibi puantajını özetle]] | [[Saha Puantajı]] | Elektrik ekibi puantajını özetle — Firma-ekip-blok puantaj; Personel genişlemesi. Çekirdek genişleme: Personel & Vardiya. |
| [[Metraj Hakediş]] | [[Metraj Hakediş]] | Poz/metraj hakediş ve kesintiler; Muhasebe genişlemesi. |
| [[Mart hakediş taslağını hazırla]] | [[Metraj Hakediş]] | Mart hakediş taslağını hazırla — Poz/metraj hakediş ve kesintiler; Muhasebe genişlemesi. |
| [[Kalıp m² farkını göster]] | [[Metraj Hakediş]] | Kalıp m² farkını göster — Poz/metraj hakediş ve kesintiler; Muhasebe genişlemesi. |
| [[Şantiye Günlüğü]] | [[Şantiye Günlüğü]] | Operasyonel günlük; Şantiye-M hazırlık (otomatik API yok). |
| [[Bugünkü günlük raporu hazırla]] | [[Şantiye Günlüğü]] | Bugünkü günlük raporu hazırla — Operasyonel günlük; Şantiye-M hazırlık (otomatik API yok). |
| [[Son 7 gün çalışılmayan günleri göster]] | [[Şantiye Günlüğü]] | Son 7 gün çalışılmayan günleri göster — Operasyonel günlük; Şantiye-M hazırlık (otomatik API yok). |
| [[Malzeme Takibi]] | [[Malzeme Takibi]] | İrsaliye kabul ve şantiye sarfiyatı. Çekirdek genişleme: e-Fatura. |
| [[Bugün gelen demiri kaydet]] | [[Malzeme Takibi]] | Bugün gelen demiri kaydet — İrsaliye kabul ve şantiye sarfiyatı. Çekirdek genişleme: e-Fatura. |
| [[Beton sarfiyatı metrajı aşıyor mu?]] | [[Malzeme Takibi]] | Beton sarfiyatı metrajı aşıyor mu? — İrsaliye kabul ve şantiye sarfiyatı. Çekirdek genişleme: e-Fatura. |
| [[Sipariş Stok]] | [[Sipariş Stok]] | Sipariş, depo, rezervasyon. |
| [[Çimento stoğunu söyle]] | [[Sipariş Stok]] | Çimento stoğunu söyle — Sipariş, depo, rezervasyon. |
| [[X şantiyesi için 20 ton ayır]] | [[Sipariş Stok]] | X şantiyesi için 20 ton ayır — Sipariş, depo, rezervasyon. |
| [[Sevkiyat İrsaliye]] | [[Sevkiyat İrsaliye]] | Sevk + e-İrsaliye. Çekirdek genişleme: e-Fatura. |
| [[Yarınki sevkiyatları listele]] | [[Sevkiyat İrsaliye]] | Yarınki sevkiyatları listele — Sevk + e-İrsaliye. Çekirdek genişleme: e-Fatura. |
| [[e-İrsaliye kes]] | [[Sevkiyat İrsaliye]] | e-İrsaliye kes — Sevk + e-İrsaliye. Çekirdek genişleme: e-Fatura. |
| [[Şantiye Teslim]] | [[Şantiye Teslim]] | Kabul/red ve yanıt. |
| [[Reddedilen sevkiyatları göster]] | [[Şantiye Teslim]] | Reddedilen sevkiyatları göster — Kabul/red ve yanıt. |
| [[Kısmi kabul kaydet]] | [[Şantiye Teslim]] | Kısmi kabul kaydet — Kabul/red ve yanıt. |

### Olmalı (0)

_Yok._

### İyi olur (12)

| Fonksiyon | Araç | Kullanım |
|---|---|---|
| [[İSG Kontrol]] | [[İSG Kontrol]] | SGP, KKD, ramak kala, belge süresi. Çekirdek genişleme: Personel & Vardiya. |
| [[Süresi dolan İSG belgelerini listele]] | [[İSG Kontrol]] | Süresi dolan İSG belgelerini listele — SGP, KKD, ramak kala, belge süresi. Çekirdek genişleme: Personel & Vardiya. |
| [[Ramak kala aç]] | [[İSG Kontrol]] | Ramak kala aç — SGP, KKD, ramak kala, belge süresi. Çekirdek genişleme: Personel & Vardiya. |
| [[Taşeron Sözleşme]] | [[Taşeron Sözleşme]] | Kapsam, birim fiyat, ölçüm, teminat, ek iş. Çekirdek genişleme: CRM. |
| [[Yeni sıva taşeron sözleşmesi oluştur]] | [[Taşeron Sözleşme]] | Yeni sıva taşeron sözleşmesi oluştur — Kapsam, birim fiyat, ölçüm, teminat, ek iş. Çekirdek genişleme: CRM. |
| [[Ek iş protokollerini göster]] | [[Taşeron Sözleşme]] | Ek iş protokollerini göster — Kapsam, birim fiyat, ölçüm, teminat, ek iş. Çekirdek genişleme: CRM. |
| [[Fiyat Liste]] | [[Fiyat Liste]] | Cari/şantiye fiyat. |
| [[Demir fiyatını güncelle]] | [[Fiyat Liste]] | Demir fiyatını güncelle — Cari/şantiye fiyat. |
| [[A carisine özel liste]] | [[Fiyat Liste]] | A carisine özel liste — Cari/şantiye fiyat. |
| [[Cari Limit]] | [[Cari Limit]] | Risk limiti/vade. Çekirdek genişleme: Muhasebe. |
| [[Limit aşan carileri göster]] | [[Cari Limit]] | Limit aşan carileri göster — Risk limiti/vade. Çekirdek genişleme: Muhasebe. |
| [[B carisine limit koy]] | [[Cari Limit]] | B carisine limit koy — Risk limiti/vade. Çekirdek genişleme: Muhasebe. |

## 5. Teknik detay
- **Entegrasyonlar:** Modül kartlarındaki entegrasyon notlarına bak; açık API yoksa panel kaydı + kullanıcı girişi.
- **Ana ekranlar:** İş listesi / kart · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Rakipler
- [[SantiyePro]]
- [[Hakedra]]
- [[ESSantiye]]
- [[Mikro]]

## 7. Kaynaklar
- [[10 İnşaat & Yapı – Kaynaklar]]
- Araştırma arşivi: `08 Arşiv/eski-docs-sektorel-arastirma/`
