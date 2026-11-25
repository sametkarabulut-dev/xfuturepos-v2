---
tip: isletme
kod: "12-05-01"
oneri_harf: C
oncelik:
gereksiz: false
oncelik_notu:
sektor: "[[12 Lojistik & Taşımacılık]]"
dal: "[[Dal – Uluslararası karayolu yük taşımacılığı]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
sayi_turu: tahmin
nace: 49.41
pazar_puani: 3
odeme_puani: 3
rekabet_puani: 2
kolaylik_puani: 2
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
  - "[[CMR Belgesi]]"
  - "[[L2 Belge]]"
  - "[[Transit Dosya]]"
  - "[[Ro-Ro Slot]]"
  - "[[Geçiş İzni]]"
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
  - "[[CMR Belgesi]]"
  - "[[TR DE seferi için CMR taslağı]]"
  - "[[CMR ye ihtirazi kayıt ekle]]"
  - "[[L2 Belge]]"
  - "[[L2 geçerlilik tarihini göster]]"
  - "[[Taşıt belgesine eklenecek plakalar]]"
  - "[[Transit Dosya]]"
  - "[[Bu seferde TIR karne durumu ne]]"
  - "[[Almanya geçiş izni eksik mi]]"
  - "[[Ro-Ro Slot]]"
  - "[[Trieste slotunu bu sevkiyata bağla]]"
  - "[[Geçiş İzni]]"
  - "[[Romanya geçiş izni kalan adet]]"
parca_sart: 25
parca_olmali: 6
parca_iyi: 10
parca_durum: tamamlandi
---
# 12-05-01 · Uluslararası karayolu yük taşımacılığı

> Sektör: [[12 Lojistik & Taşımacılık]] · Öncelik: **2.8** / 5 · Öneri: **C**
> Puanlar tahmindir: pazar 3 · ödeme 3 · rekabet boşluğu 2 · kolaylık 2 · aciliyet 4

## 1. Özet
Sınır geçen ticari karayolu seferi; belge bugün çoğunlukla L2’dir.

- **İşletme sayısı:** bulunamadı
- **NACE:** 49.41
- **Sayı türü:** tahmin

## 2. Günlük iş akışı
1. CMR
2. geçiş belgesi
3. gümrük müşaviri koordinasyonu
4. dövizli navlun
5. dönüş yükü.

```mermaid
flowchart LR
  S1["CMR"] --> S2
  S2["geçiş belgesi"] --> S3
  S3["gümrük müşaviri koordinasyonu"] --> S4
  S4["dövizli navlun"] --> S5
  S5["dönüş yükü."]
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

41 parça · 25 şart · 6 olmalı · 10 iyi olur

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
| [[CMR Belgesi]] | [[CMR Belgesi]] | CMR taşıma senedi alanları ve ihtirazi kayıt; ev eşyası taşınması CMR dışı. |
| [[TR DE seferi için CMR taslağı]] | [[CMR Belgesi]] | TR DE seferi için CMR taslağı — CMR taşıma senedi alanları ve ihtirazi kayıt; ev eşyası taşınması CMR dışı. |
| [[CMR ye ihtirazi kayıt ekle]] | [[CMR Belgesi]] | CMR ye ihtirazi kayıt ekle — CMR taşıma senedi alanları ve ihtirazi kayıt; ev eşyası taşınması CMR dışı. |
| [[L2 Belge]] | [[L2 Belge]] | L2 yetki ve taşıt belgesi takibi; U-ETDS L2 yükümlülüğü. |
| [[L2 geçerlilik tarihini göster]] | [[L2 Belge]] | L2 geçerlilik tarihini göster — L2 yetki ve taşıt belgesi takibi; U-ETDS L2 yükümlülüğü. |
| [[Taşıt belgesine eklenecek plakalar]] | [[L2 Belge]] | Taşıt belgesine eklenecek plakalar — L2 yetki ve taşıt belgesi takibi; U-ETDS L2 yükümlülüğü. |
| [[Transit Dosya]] | [[Transit Dosya]] | TIR karne / NCTS / geçiş izni checklist; hangisinin kullanılacağı güzergâha bağlı. |
| [[Bu seferde TIR karne durumu ne]] | [[Transit Dosya]] | Bu seferde TIR karne durumu ne — TIR karne / NCTS / geçiş izni checklist; hangisinin kullanılacağı güzergâha bağlı. |
| [[Almanya geçiş izni eksik mi]] | [[Transit Dosya]] | Almanya geçiş izni eksik mi — TIR karne / NCTS / geçiş izni checklist; hangisinin kullanılacağı güzergâha bağlı. |

### Olmalı (6)

| Fonksiyon | Araç | Kullanım |
|---|---|---|
| [[U-ETDS Köprüsü]] | [[U-ETDS Köprüsü]] | Sefer, yük, şoför bildirimi için SOAP alanlarını doldurur; gönderim onaylıdır. K1/K3/C3/L1/L2/N1/N2 (TM’de C1/K2) için. |
| [[34 ABC 123 seferini U-ETDS için hazırla]] | [[U-ETDS Köprüsü]] | 34 ABC 123 seferini U-ETDS için hazırla — Sefer, yük, şoför bildirimi için SOAP alanlarını doldurur; gönderim onaylıdır. K1/K3/C3/L1/L2/N1/N2 (TM’de C1/K2) için. |
| [[Bugün bildirilmemiş seferleri göster]] | [[U-ETDS Köprüsü]] | Bugün bildirilmemiş seferleri göster — Sefer, yük, şoför bildirimi için SOAP alanlarını doldurur; gönderim onaylıdır. K1/K3/C3/L1/L2/N1/N2 (TM’de C1/K2) için. |
| [[Araç Şoför]] | [[Araç Şoför]] | Plaka, taşıt kartı, SRC/psikoteknik bitiş ve şoför-araç eşlemesi. Personel çekirdeğinin filo genişlemesi. |
| [[SRC si 30 günde bitecek şoförleri göster]] | [[Araç Şoför]] | SRC si 30 günde bitecek şoförleri göster — Plaka, taşıt kartı, SRC/psikoteknik bitiş ve şoför-araç eşlemesi. Personel çekirdeğinin filo genişlemesi. |
| [[34 XYZ 45 plakasını Mehmet e ata]] | [[Araç Şoför]] | 34 XYZ 45 plakasını Mehmet e ata — Plaka, taşıt kartı, SRC/psikoteknik bitiş ve şoför-araç eşlemesi. Personel çekirdeğinin filo genişlemesi. |

### İyi olur (10)

| Fonksiyon | Araç | Kullanım |
|---|---|---|
| [[Hasar Dosyası]] | [[Hasar Dosyası]] | Hasar/kayıp dosyası, tutanak ve sigorta iletim checklisti; tazminat ödemesi AI onayı olmadan yok. |
| [[Sevkiyat 441 için hasar dosyası aç]] | [[Hasar Dosyası]] | Sevkiyat 441 için hasar dosyası aç — Hasar/kayıp dosyası, tutanak ve sigorta iletim checklisti; tazminat ödemesi AI onayı olmadan yok. |
| [[Açık hasar dosyalarını özetle]] | [[Hasar Dosyası]] | Açık hasar dosyalarını özetle — Hasar/kayıp dosyası, tutanak ve sigorta iletim checklisti; tazminat ödemesi AI onayı olmadan yok. |
| [[Araç Takip]] | [[Araç Takip]] | Harici filo takip konumunu sevkiyata bağlar; marka API iddiası doğrulanmadan bağlanır. |
| [[34 ABC 123 son bilinen konum]] | [[Araç Takip]] | 34 ABC 123 son bilinen konum — Harici filo takip konumunu sevkiyata bağlar; marka API iddiası doğrulanmadan bağlanır. |
| [[ETA sı geciken araçları göster]] | [[Araç Takip]] | ETA sı geciken araçları göster — Harici filo takip konumunu sevkiyata bağlar; marka API iddiası doğrulanmadan bağlanır. |
| [[Ro-Ro Slot]] | [[Ro-Ro Slot]] | Feribot/Ro-Ro rezervasyonunu sevkiyat ETA’sına bağlar. |
| [[Trieste slotunu bu sevkiyata bağla]] | [[Ro-Ro Slot]] | Trieste slotunu bu sevkiyata bağla — Feribot/Ro-Ro rezervasyonunu sevkiyat ETA’sına bağlar. |
| [[Geçiş İzni]] | [[Geçiş İzni]] | Ülke geçiş belgesi stok ve kullanım kaydı. |
| [[Romanya geçiş izni kalan adet]] | [[Geçiş İzni]] | Romanya geçiş izni kalan adet — Ülke geçiş belgesi stok ve kullanım kaydı. |

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
