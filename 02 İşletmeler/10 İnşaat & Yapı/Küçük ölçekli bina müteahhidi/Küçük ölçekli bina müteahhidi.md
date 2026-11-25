---
tip: isletme
kod: "10-01-01"
oneri_harf: A
oncelik:
gereksiz: false
oncelik_notu:
sektor: "[[10 İnşaat & Yapı]]"
dal: "[[Dal – Küçük ölçekli bina müteahhidi]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "KOSGEB inşaat KOBİ kümesi içinde; alt kırılım bulunamadı"
sayi_turu: tahmin
nace: 41.20
pazar_puani: 5
odeme_puani: 4
rekabet_puani: 2
kolaylik_puani: 3
aciliyet_puani: 5
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
  - "[[Ruhsat Takibi]]"
  - "[[İş Programı]]"
  - "[[Maliyet Bütçe]]"
  - "[[Şef Atama]]"
  - "[[Keşif Teklif]]"
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
  - "[[Ruhsat Takibi]]"
  - "[[Ruhsat bekleyen projeleri göster]]"
  - "[[İskan evrak listesini çıkar]]"
  - "[[İş Programı]]"
  - "[[Kaba inşaat bitişini kaydır]]"
  - "[[Kritik gecikmeleri özetle]]"
  - "[[Maliyet Bütçe]]"
  - "[[Bu ay bütçe sapmasını göster]]"
  - "[[Demir kalemini artır]]"
  - "[[Şef Atama]]"
  - "[[Bu işe şef ata]]"
  - "[[Şefin aktif m² toplamını göster]]"
  - "[[Keşif Teklif]]"
  - "[[Villaya teklif hazırla]]"
  - "[[Teklifi sözleşmeye çevir]]"
parca_sart: 31
parca_olmali: 0
parca_iyi: 12
parca_durum: tamamlandi
---
# 10-01-01 · Küçük ölçekli bina müteahhidi

> Sektör: [[10 İnşaat & Yapı]] · Öncelik: **3.8** / 5 · Öneri: **A**
> Puanlar tahmindir: pazar 5 · ödeme 4 · rekabet boşluğu 2 · kolaylık 3 · aciliyet 5

## 1. Özet
Ruhsatlı konut, işyeri veya esaslı tadilatı kendi yetki belgesiyle üstlenen firma.

- **İşletme sayısı:** KOSGEB inşaat KOBİ kümesi içinde; alt kırılım bulunamadı
- **NACE:** 41.20
- **Sayı türü:** tahmin

## 2. Günlük iş akışı
1. Yetki belgesi
2. şantiye şefi
3. malzeme
4. taşeron
5. yapı denetim evrakı
6. işçilik bildirimi.

```mermaid
flowchart LR
  S1["Yetki belgesi"] --> S2
  S2["şantiye şefi"] --> S3
  S3["malzeme"] --> S4
  S4["taşeron"] --> S5
  S5["yapı denetim evrakı"] --> S6
  S6["işçilik bildirimi."]
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
| [[Ruhsat Takibi]] | [[Ruhsat Takibi]] | Ruhsat-iskan evrak ve adım takibi. |
| [[Ruhsat bekleyen projeleri göster]] | [[Ruhsat Takibi]] | Ruhsat bekleyen projeleri göster — Ruhsat-iskan evrak ve adım takibi. |
| [[İskan evrak listesini çıkar]] | [[Ruhsat Takibi]] | İskan evrak listesini çıkar — Ruhsat-iskan evrak ve adım takibi. |
| [[İş Programı]] | [[İş Programı]] | Kilometre taşı ve gecikme. |
| [[Kaba inşaat bitişini kaydır]] | [[İş Programı]] | Kaba inşaat bitişini kaydır — Kilometre taşı ve gecikme. |
| [[Kritik gecikmeleri özetle]] | [[İş Programı]] | Kritik gecikmeleri özetle — Kilometre taşı ve gecikme. |
| [[Maliyet Bütçe]] | [[Maliyet Bütçe]] | Keşif vs gerçekleşen. Çekirdek genişleme: Muhasebe. |
| [[Bu ay bütçe sapmasını göster]] | [[Maliyet Bütçe]] | Bu ay bütçe sapmasını göster — Keşif vs gerçekleşen. Çekirdek genişleme: Muhasebe. |
| [[Demir kalemini artır]] | [[Maliyet Bütçe]] | Demir kalemini artır — Keşif vs gerçekleşen. Çekirdek genişleme: Muhasebe. |

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
| [[Şef Atama]] | [[Şef Atama]] | Şantiye şefi atama ve limit. |
| [[Bu işe şef ata]] | [[Şef Atama]] | Bu işe şef ata — Şantiye şefi atama ve limit. |
| [[Şefin aktif m² toplamını göster]] | [[Şef Atama]] | Şefin aktif m² toplamını göster — Şantiye şefi atama ve limit. |
| [[Keşif Teklif]] | [[Keşif Teklif]] | Birim fiyatlı teklif. |
| [[Villaya teklif hazırla]] | [[Keşif Teklif]] | Villaya teklif hazırla — Birim fiyatlı teklif. |
| [[Teklifi sözleşmeye çevir]] | [[Keşif Teklif]] | Teklifi sözleşmeye çevir — Birim fiyatlı teklif. |

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
