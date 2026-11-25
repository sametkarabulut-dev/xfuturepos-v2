---
tip: isletme
kod: "12-03-01"
oneri_harf: B
oncelik:
gereksiz: false
oncelik_notu:
sektor: "[[12 Lojistik & Taşımacılık]]"
dal: "[[Dal – Nakliyat ambarı]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
sayi_turu: tahmin
nace: 52.29
pazar_puani: 3
odeme_puani: 3
rekabet_puani: 3
kolaylik_puani: 3
aciliyet_puani: 4
ihtiyaclar:
  - "[[Sevkiyat kartı]]"
  - "[[Navlun teklifi]]"
  - "[[Araç / şoför]]"
  - "[[Teslim kanıtı]]"
  - "[[e-Belge]]"
  - "[[U-ETDS köprüsü]]"
  - "[[Belge / yetki takibi]]"
  - "[[Kurye / durak rotası]]"
moduller:
  - "[[Muhasebe ve Gelir-Gider]]"
  - "[[e-Fatura ve e-Arşiv]]"
  - "[[CRM]]"
  - "[[Personel ve Vardiya]]"
  - "[[Raporlar]]"
  - "[[AI Asistan]]"
  - "[[Ayarlar]]"
  - "[[Sevkiyat Kartı]]"
  - "[[Navlun Teklifi]]"
  - "[[U-ETDS Köprüsü]]"
  - "[[Teslim Kanıtı]]"
  - "[[Araç Şoför]]"
  - "[[Hasar Dosyası]]"
  - "[[Araç Takip]]"
  - "[[Parsiyel Toplama]]"
  - "[[Hat Seferi]]"
  - "[[Ambar Stok]]"
  - "[[G1 Acente]]"
  - "[[N Belge]]"
rakipler:
  - "[[U-ETDS]]"
  - "[[Filo / TMS paketleri]]"
fonksiyonlar:
  - "[[Muhasebe ve Gelir-Gider]]"
  - "[[e-Fatura ve e-Arşiv]]"
  - "[[CRM]]"
  - "[[Personel ve Vardiya]]"
  - "[[Raporlar]]"
  - "[[AI Asistan]]"
  - "[[Ayarlar]]"
  - "[[Sevkiyat Kartı]]"
  - "[[Bugün yüklenen 3 sevkiyatı listele]]"
  - "[[ABC Ltd sevkiyatını yolda yap]]"
  - "[[Navlun Teklifi]]"
  - "[[İstanbul Ankara 12 ton navlun taslağı çıkar]]"
  - "[[Geçen ayki ABC fiyatını bu işe kopyala]]"
  - "[[U-ETDS Köprüsü]]"
  - "[[34 ABC 123 seferini U-ETDS için hazırla]]"
  - "[[Bugün bildirilmemiş seferleri göster]]"
  - "[[Teslim Kanıtı]]"
  - "[[Sevkiyat 34-882 teslim kanıtını aç]]"
  - "[[Dün reddedilen teslimleri listele]]"
  - "[[Araç Şoför]]"
  - "[[SRC si 30 günde bitecek şoförleri göster]]"
  - "[[34 XYZ 45 plakasını Mehmet e ata]]"
  - "[[Hasar Dosyası]]"
  - "[[Sevkiyat 441 için hasar dosyası aç]]"
  - "[[Açık hasar dosyalarını özetle]]"
  - "[[Araç Takip]]"
  - "[[34 ABC 123 son bilinen konum]]"
  - "[[ETA sı geciken araçları göster]]"
  - "[[Parsiyel Toplama]]"
  - "[[Ankara hattına 4 parça ekle]]"
  - "[[Bugün kabul edilen parçaları listele]]"
  - "[[Hat Seferi]]"
  - "[[İstanbul Ankara hattı doluluk oranı]]"
  - "[[Hat 3 ü kalkışa kapat]]"
  - "[[Ambar Stok]]"
  - "[[Raf A-12 de ne var]]"
  - "[[3 gündür bekleyen parçalar]]"
  - "[[G1 Acente]]"
  - "[[G1 sözleşmeli ambarları listele]]"
  - "[[N Belge]]"
  - "[[N2 belgesi bitiş tarihi]]"
  - "[[Şube alan uyarısı var mı]]"
parca_sart: 25
parca_olmali: 6
parca_iyi: 11
parca_durum: tamamlandi
---
# 12-03-01 · Nakliyat ambarı

> Sektör: [[12 Lojistik & Taşımacılık]] · Öncelik: **3.2** / 5 · Öneri: **B**
> Puanlar tahmindir: pazar 3 · ödeme 3 · rekabet boşluğu 3 · kolaylık 3 · aciliyet 4

## 1. Özet
Parça yükü şubede kabul edip aynı yöne giden hat aracında birleştiren işletme.

- **İşletme sayısı:** bulunamadı
- **NACE:** 52.29
- **Sayı türü:** tahmin

## 2. Günlük iş akışı
1. Kabul
2. ölçüm
3. hat seçimi
4. aktarma
5. varış şubesinden teslim.

```mermaid
flowchart LR
  S1["Kabul"] --> S2
  S2["ölçüm"] --> S3
  S3["hat seçimi"] --> S4
  S4["aktarma"] --> S5
  S5["varış şubesinden teslim."]
```

## 3. İhtiyaçlar ve sorunlar
| İhtiyaç | Bugün nasıl çözüyorlar | Etkisi |
|---|---|---|
| [[Sevkiyat kartı]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Navlun teklifi]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Araç / şoför]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Teslim kanıtı]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[e-Belge]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[U-ETDS köprüsü]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Belge / yetki takibi]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |
| [[Kurye / durak rotası]] | Excel / WhatsApp / portal (tahmin) | Zaman, hata, uyum riski |

## 4. Parçalar

42 parça · 25 şart · 6 olmalı · 11 iyi olur

### Şart (25)

| Fonksiyon | Araç | Kullanım |
|---|---|---|
| [[Muhasebe ve Gelir-Gider]] | [[Muhasebe ve Gelir-Gider]] | Gelir, gider, cari, kasa ve banka. Sektör belgesi para kaydını buraya düşürür. |
| [[e-Fatura ve e-Arşiv]] | [[e-Fatura ve e-Arşiv]] | Satış belgesi taslağı; gönderim entegratör + onayla. |
| [[CRM]] | [[CRM]] | Kişi/firma kartı, iletişim, not; sektör alanları karta eklenir. |
| [[Personel ve Vardiya]] | [[Personel ve Vardiya]] | Personel kartı, vardiya, puantaj. Bordro/SGK kesilmez. |
| [[Raporlar]] | [[Raporlar]] | Ciro, tahsilat, açık iş ve personel özeti. |
| [[AI Asistan]] | [[AI Asistan]] | Komut çalıştırır, taslak üretir; yüksek etkili işlem onaysız bitmez. |
| [[Ayarlar]] | [[Ayarlar]] | İşletme, belge, bildirim ve entegrasyon ayarları. |
| [[Sevkiyat Kartı]] | [[Sevkiyat Kartı]] | Yük/sevkiyat yaşam döngüsü: talep, yükleme, yolda, teslim; gönderici/alıcı, tonaj ve adres tek kartta. |
| [[Bugün yüklenen 3 sevkiyatı listele]] | [[Sevkiyat Kartı]] | Bugün yüklenen 3 sevkiyatı listele — Yük/sevkiyat yaşam döngüsü: talep, yükleme, yolda, teslim; gönderici/alıcı, tonaj ve adres tek kartta. |
| [[ABC Ltd sevkiyatını yolda yap]] | [[Sevkiyat Kartı]] | ABC Ltd sevkiyatını yolda yap — Yük/sevkiyat yaşam döngüsü: talep, yükleme, yolda, teslim; gönderici/alıcı, tonaj ve adres tek kartta. |
| [[Navlun Teklifi]] | [[Navlun Teklifi]] | Tonaj, güzergâh ve bekleme ile navlun taslağı; müşteriye göndermeden önce insan onayı. |
| [[İstanbul Ankara 12 ton navlun taslağı çıkar]] | [[Navlun Teklifi]] | İstanbul Ankara 12 ton navlun taslağı çıkar — Tonaj, güzergâh ve bekleme ile navlun taslağı; müşteriye göndermeden önce insan onayı. |
| [[Geçen ayki ABC fiyatını bu işe kopyala]] | [[Navlun Teklifi]] | Geçen ayki ABC fiyatını bu işe kopyala — Tonaj, güzergâh ve bekleme ile navlun taslağı; müşteriye göndermeden önce insan onayı. |
| [[Teslim Kanıtı]] | [[Teslim Kanıtı]] | Alıcı imza/foto/red ve hasar notu; faturalama için çekirdek e-Fatura sürecine veri bırakır. |
| [[Sevkiyat 34-882 teslim kanıtını aç]] | [[Teslim Kanıtı]] | Sevkiyat 34-882 teslim kanıtını aç — Alıcı imza/foto/red ve hasar notu; faturalama için çekirdek e-Fatura sürecine veri bırakır. |
| [[Dün reddedilen teslimleri listele]] | [[Teslim Kanıtı]] | Dün reddedilen teslimleri listele — Alıcı imza/foto/red ve hasar notu; faturalama için çekirdek e-Fatura sürecine veri bırakır. |
| [[Parsiyel Toplama]] | [[Parsiyel Toplama]] | Parça yük kabul, etiketleme ve hat aracına konsolidasyon. |
| [[Ankara hattına 4 parça ekle]] | [[Parsiyel Toplama]] | Ankara hattına 4 parça ekle — Parça yük kabul, etiketleme ve hat aracına konsolidasyon. |
| [[Bugün kabul edilen parçaları listele]] | [[Parsiyel Toplama]] | Bugün kabul edilen parçaları listele — Parça yük kabul, etiketleme ve hat aracına konsolidasyon. |
| [[Hat Seferi]] | [[Hat Seferi]] | Hat aracı kalkış, doluluk ve varış ambarında aktarma. |
| [[İstanbul Ankara hattı doluluk oranı]] | [[Hat Seferi]] | İstanbul Ankara hattı doluluk oranı — Hat aracı kalkış, doluluk ve varış ambarında aktarma. |
| [[Hat 3 ü kalkışa kapat]] | [[Hat Seferi]] | Hat 3 ü kalkışa kapat — Hat aracı kalkış, doluluk ve varış ambarında aktarma. |
| [[Ambar Stok]] | [[Ambar Stok]] | Kapalı ambar giriş-çıkış, göz/yer ve bekleyen parça arama. |
| [[Raf A-12 de ne var]] | [[Ambar Stok]] | Raf A-12 de ne var — Kapalı ambar giriş-çıkış, göz/yer ve bekleyen parça arama. |
| [[3 gündür bekleyen parçalar]] | [[Ambar Stok]] | 3 gündür bekleyen parçalar — Kapalı ambar giriş-çıkış, göz/yer ve bekleyen parça arama. |

### Olmalı (6)

| Fonksiyon | Araç | Kullanım |
|---|---|---|
| [[U-ETDS Köprüsü]] | [[U-ETDS Köprüsü]] | Sefer, yük, şoför bildirimi için SOAP alanlarını doldurur; gönderim onaylıdır. K1/K3/C3/L1/L2/N1/N2 (TM’de C1/K2) için. |
| [[34 ABC 123 seferini U-ETDS için hazırla]] | [[U-ETDS Köprüsü]] | 34 ABC 123 seferini U-ETDS için hazırla — Sefer, yük, şoför bildirimi için SOAP alanlarını doldurur; gönderim onaylıdır. K1/K3/C3/L1/L2/N1/N2 (TM’de C1/K2) için. |
| [[Bugün bildirilmemiş seferleri göster]] | [[U-ETDS Köprüsü]] | Bugün bildirilmemiş seferleri göster — Sefer, yük, şoför bildirimi için SOAP alanlarını doldurur; gönderim onaylıdır. K1/K3/C3/L1/L2/N1/N2 (TM’de C1/K2) için. |
| [[Araç Şoför]] | [[Araç Şoför]] | Plaka, taşıt kartı, SRC/psikoteknik bitiş ve şoför-araç eşlemesi. Personel çekirdeğinin filo genişlemesi. |
| [[SRC si 30 günde bitecek şoförleri göster]] | [[Araç Şoför]] | SRC si 30 günde bitecek şoförleri göster — Plaka, taşıt kartı, SRC/psikoteknik bitiş ve şoför-araç eşlemesi. Personel çekirdeğinin filo genişlemesi. |
| [[34 XYZ 45 plakasını Mehmet e ata]] | [[Araç Şoför]] | 34 XYZ 45 plakasını Mehmet e ata — Plaka, taşıt kartı, SRC/psikoteknik bitiş ve şoför-araç eşlemesi. Personel çekirdeğinin filo genişlemesi. |

### İyi olur (11)

| Fonksiyon | Araç | Kullanım |
|---|---|---|
| [[Hasar Dosyası]] | [[Hasar Dosyası]] | Hasar/kayıp dosyası, tutanak ve sigorta iletim checklisti; tazminat ödemesi AI onayı olmadan yok. |
| [[Sevkiyat 441 için hasar dosyası aç]] | [[Hasar Dosyası]] | Sevkiyat 441 için hasar dosyası aç — Hasar/kayıp dosyası, tutanak ve sigorta iletim checklisti; tazminat ödemesi AI onayı olmadan yok. |
| [[Açık hasar dosyalarını özetle]] | [[Hasar Dosyası]] | Açık hasar dosyalarını özetle — Hasar/kayıp dosyası, tutanak ve sigorta iletim checklisti; tazminat ödemesi AI onayı olmadan yok. |
| [[Araç Takip]] | [[Araç Takip]] | Harici filo takip konumunu sevkiyata bağlar; marka API iddiası doğrulanmadan bağlanır. |
| [[34 ABC 123 son bilinen konum]] | [[Araç Takip]] | 34 ABC 123 son bilinen konum — Harici filo takip konumunu sevkiyata bağlar; marka API iddiası doğrulanmadan bağlanır. |
| [[ETA sı geciken araçları göster]] | [[Araç Takip]] | ETA sı geciken araçları göster — Harici filo takip konumunu sevkiyata bağlar; marka API iddiası doğrulanmadan bağlanır. |
| [[G1 Acente]] | [[G1 Acente]] | Başka N belgesi adına yük kabul eden G1 acente sözleşmeleri. |
| [[G1 sözleşmeli ambarları listele]] | [[G1 Acente]] | G1 sözleşmeli ambarları listele — Başka N belgesi adına yük kabul eden G1 acente sözleşmeleri. |
| [[N Belge]] | [[N Belge]] | N1/N2 süre ve şube alan uygunluk notu. |
| [[N2 belgesi bitiş tarihi]] | [[N Belge]] | N2 belgesi bitiş tarihi — N1/N2 süre ve şube alan uygunluk notu. |
| [[Şube alan uyarısı var mı]] | [[N Belge]] | Şube alan uyarısı var mı — N1/N2 süre ve şube alan uygunluk notu. |

## 5. Teknik detay
- **Entegrasyonlar:** Modül kartlarındaki entegrasyon notlarına bak; açık API yoksa panel kaydı + kullanıcı girişi.
- **Ana ekranlar:** İş listesi / kart · Takvim veya pipeline · Tahsilat · Rapor
- **Veri yapısı:** `Cari → İşKaydı → Belge/Tahsilat → Hatırlatma (onay kuyruğu)`

## 6. Rakipler
- [[U-ETDS]]
- [[Filo / TMS paketleri]]

## 7. Kaynaklar
- [[12 Lojistik & Taşımacılık – Kaynaklar]]
- Araştırma arşivi: `08 Arşiv/eski-docs-sektorel-arastirma/`
