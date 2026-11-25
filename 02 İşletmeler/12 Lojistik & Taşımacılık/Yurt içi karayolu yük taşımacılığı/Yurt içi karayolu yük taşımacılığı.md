---
tip: isletme
kod: "12-01-01"
oneri_harf: A
oncelik:
gereksiz: false
oncelik_notu:
sektor: "[[12 Lojistik & Taşımacılık]]"
dal: "[[Dal – Yurt içi karayolu yük taşımacılığı]]"
durum: tamamlandi
olcek: ['mikro', 'kucuk-orta']
isletme_sayisi: "bulunamadı"
sayi_turu: tahmin
nace: 49.41
pazar_puani: 5
odeme_puani: 4
rekabet_puani: 2
kolaylik_puani: 3
aciliyet_puani: 5
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
  - "[[Sefer Planı]]"
  - "[[K1 Belge]]"
  - "[[Yol Masrafı]]"
  - "[[Takograf Uyarı]]"
  - "[[Taşıma İrsaliye]]"
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
  - "[[Sefer Planı]]"
  - "[[Yarınki 5 seferi planla]]"
  - "[[34 DEF 01 i bu sefere ata]]"
  - "[[K1 Belge]]"
  - "[[K1 belgesi ne zaman bitiyor]]"
  - "[[Taşıt kartı olmayan plakaları listele]]"
  - "[[Yol Masrafı]]"
  - "[[Sefer 12 ye 2500 TL mazot ekle]]"
  - "[[Bu haftanın mazot toplamını söyle]]"
  - "[[Takograf Uyarı]]"
  - "[[Bugün dinlenme limiti yaklaşan şoförler]]"
  - "[[Taşıma İrsaliye]]"
  - "[[Sefer 8 için taşıma irsaliyesi taslağı]]"
  - "[[Bugün irsaliyesiz kalkan seferler]]"
parca_sart: 25
parca_olmali: 6
parca_iyi: 11
parca_durum: tamamlandi
---
# 12-01-01 · Yurt içi karayolu yük taşımacılığı

> Sektör: [[12 Lojistik & Taşımacılık]] · Öncelik: **3.8** / 5 · Öneri: **A**
> Puanlar tahmindir: pazar 5 · ödeme 4 · rekabet boşluğu 2 · kolaylık 3 · aciliyet 5

## 1. Özet
Başka firmaların yükünü Türkiye içinde ticari olarak taşıyan filo.

- **İşletme sayısı:** bulunamadı
- **NACE:** 49.41
- **Sayı türü:** tahmin

## 2. Günlük iş akışı
1. Yükü araca
2. SRC’li sürücüye bağlar
3. taşıma belgesini çıkarır
4. U-ETDS’ye işler
5. navlun
6. yakıtı kapatır.

```mermaid
flowchart LR
  S1["Yükü araca"] --> S2
  S2["SRC’li sürücüye bağlar"] --> S3
  S3["taşıma belgesini çıkarır"] --> S4
  S4["U-ETDS’ye işler"] --> S5
  S5["navlun"] --> S6
  S6["yakıtı kapatır."]
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
| [[Sefer Planı]] | [[Sefer Planı]] | Güzergâh, yükleme-boşaltma penceresi ve araç-şoför ataması; boş dönüş notu. |
| [[Yarınki 5 seferi planla]] | [[Sefer Planı]] | Yarınki 5 seferi planla — Güzergâh, yükleme-boşaltma penceresi ve araç-şoför ataması; boş dönüş notu. |
| [[34 DEF 01 i bu sefere ata]] | [[Sefer Planı]] | 34 DEF 01 i bu sefere ata — Güzergâh, yükleme-boşaltma penceresi ve araç-şoför ataması; boş dönüş notu. |
| [[K1 Belge]] | [[K1 Belge]] | K1 yetki belgesi ve eki taşıt kartı süre/uyarma takibi. |
| [[K1 belgesi ne zaman bitiyor]] | [[K1 Belge]] | K1 belgesi ne zaman bitiyor — K1 yetki belgesi ve eki taşıt kartı süre/uyarma takibi. |
| [[Taşıt kartı olmayan plakaları listele]] | [[K1 Belge]] | Taşıt kartı olmayan plakaları listele — K1 yetki belgesi ve eki taşıt kartı süre/uyarma takibi. |
| [[Yol Masrafı]] | [[Yol Masrafı]] | Mazot, köprü, bekleme masraflarını sefere bağlayıp kârlılık taslağı üretir. |
| [[Sefer 12 ye 2500 TL mazot ekle]] | [[Yol Masrafı]] | Sefer 12 ye 2500 TL mazot ekle — Mazot, köprü, bekleme masraflarını sefere bağlayıp kârlılık taslağı üretir. |
| [[Bu haftanın mazot toplamını söyle]] | [[Yol Masrafı]] | Bu haftanın mazot toplamını söyle — Mazot, köprü, bekleme masraflarını sefere bağlayıp kârlılık taslağı üretir. |

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
| [[Takograf Uyarı]] | [[Takograf Uyarı]] | Planlanan sürüşe göre dinlenme/süre aşımı hatırlatması; cihaz API’si bağlanmadan çalışır. |
| [[Bugün dinlenme limiti yaklaşan şoförler]] | [[Takograf Uyarı]] | Bugün dinlenme limiti yaklaşan şoförler — Planlanan sürüşe göre dinlenme/süre aşımı hatırlatması; cihaz API’si bağlanmadan çalışır. |
| [[Taşıma İrsaliye]] | [[Taşıma İrsaliye]] | VUK taşıma irsaliyesi alanları; sevk e-irsaliyesi ile karıştırılmaz. |
| [[Sefer 8 için taşıma irsaliyesi taslağı]] | [[Taşıma İrsaliye]] | Sefer 8 için taşıma irsaliyesi taslağı — VUK taşıma irsaliyesi alanları; sevk e-irsaliyesi ile karıştırılmaz. |
| [[Bugün irsaliyesiz kalkan seferler]] | [[Taşıma İrsaliye]] | Bugün irsaliyesiz kalkan seferler — VUK taşıma irsaliyesi alanları; sevk e-irsaliyesi ile karıştırılmaz. |

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
