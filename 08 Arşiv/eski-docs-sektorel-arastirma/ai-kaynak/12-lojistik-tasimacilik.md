---
tip: sektor
durum: tamamlandi
sektor_id: "12"
is_modeli: sevkiyat
ortak_cekirdek: 00-tum-sektorler-ortak.md
---

# 12 Lojistik & Taşımacılık

## Ortak çekirdek
00.01 Muhasebe ve Gelir-Gider, 00.02 e-Fatura ve e-Arşiv, 00.03 CRM, 00.04 Personel ve Vardiya, 00.05 Raporlar, 00.06 AI Asistan, 00.07 Ayarlar bu dosyada yoktur. Tanım `00-tum-sektorler-ortak.md` içindedir.

## Özet
1–50 çalışanlı yük lojistiği, işin nereye oturduğuna göre ayrılır: sefer, ambar hattı, şehir içi çok durak, ev taşıma, filosuz organizasyon ve başkasının malını depoda hazırlama. Karayolu Taşıma Yönetmeliği bunları ayrı yetki belgelerine bağlar; ürün kümesi belge kodu değildir. 14 Ocak 2023 değişikliğiyle mevcut C2 belgeleri L2’ye çevrilmiş ve yeni C2 düzenlenmemiştir.

Günün döngüsü yükü kabul etmek, aracı ve sürücüyü bağlamak, taşıma belgesini çıkarmak ve navlunu kapatmaktır. C3, K1, K3, L1, L2, N1 ve N2 sahipleri sefer bilgisini taşıma başlayıncaya kadar U-ETDS’ye işler. Bakanlık bildirimin e-Devlet, web servisi ve UETDS uygulamasıyla yapılabildiğini duyurmuştur.

UTİKAD raporu ulaştırma ve depolamanın 2024 GSYH payını TÜİK’e dayanarak %8,2 verir. Bu, 1–50 çalışanlı firma sayısı değildir. Güncel yetki belgesi envanteri açık tablo olarak bulunamadı.

Karar: Uluslararası karayolu ayrı durur çünkü sefer fiilen sürer; ikinci bir lojistik işletmeciliği kopyası açılmaz.

## Sınırlar
- Soğuk zincir ve tehlikeli madde ayrı alt sektör değildir. Şehirler arası frigorifik 12.01, sınır ötesi 12.02, şehir içi çok duraklı gıda turu 12.04’tedir.
- Tarifeli ulusal kargo ağları (M2) bu bandın dışındadır. Tasnif edip hat aracına veren iş 12.03, tasnifsiz aynı gün kurye 12.04’tür.
- K2 ve C1 yalnızca kendi esas işinin yükünü taşır; üreticinin kendi sevkiyatı 13’tedir. Yolcu, liman işletmeciliği ve gümrük müşavirliği dışarıdadır. 12.06 gümrük müşavirini koordine eder, beyannameyi yazmaz.

## Doğrulanamayan
- Güncel K1, N2, P1 ve TİO firma sayıları.
- Excel veya WhatsApp kullanım oranı ve bağımsız kayıp rakamı.
- U-ETDS için bakanlıkça yayımlanmış yazılım entegratör listesi.
- Araç takip markalarının açık API dokümanı bu taramada yoktu. Google Routes API sonraki turda rota için doğrulandı; filo telematiği doğrulanmadı.

## Alt sektörler
### 12.01 Yurt içi karayolu yük taşımacılığı

- aciklama: Başka firmaların yükünü Türkiye içinde ticari olarak taşıyan filo.
- gunluk_is: Yükü araca ve SRC’li sürücüye bağlar, taşıma belgesini çıkarır, U-ETDS’ye işler, navlun ve yakıtı kapatır.
- ai: WhatsApp yük metninden sefer taslağı ve U-ETDS alanlarını hazırlar; gönderim onayda kalır.

### 12.02 Uluslararası karayolu yük taşımacılığı

- aciklama: Sınır geçen ticari karayolu seferi; belge bugün çoğunlukla L2’dir.
- gunluk_is: CMR, geçiş belgesi, gümrük müşaviri koordinasyonu, dövizli navlun ve dönüş yükü.
- ai: Evrak listesi, belge bitiş hatırlatması ve dövizli hakediş taslağı çıkarır.

### 12.03 Nakliyat ambarı

- aciklama: Parça yükü şubede kabul edip aynı yöne giden hat aracında birleştiren işletme.
- gunluk_is: Kabul, ölçüm, hat seçimi, aktarma ve varış şubesinden teslim.
- ai: Parça yükü hat aracına ağırlık ve hacimle önerir; yanlış şube ve eksik tahsilatı işaretler.

### 12.04 Şehir içi kurye ve dağıtım

- aciklama: İl içi veya komşu ilçelerde tasnif olmadan taşınan kurye gönderisi.
- gunluk_is: Çok duraklı tur, teslim kanıtı ve sık tahsilat.
- ai: Durakları tura dizer, teslim notundan iade çıkarır, varış metnini hazırlar.

### 12.05 Ev ve büro taşımacılığı

- aciklama: Ev veya büronun ticari taşınması; yurt içi K3, uluslararası kapsam C3.
- gunluk_is: Keşif, hacim, paketleme, ekip, araç ve taşıma günü.
- ai: Keşif notundan hacim, ekip süresi ve teklif taslağı üretir; fiyat onaya kalır.

### 12.06 Taşıma organizatörlüğü ve acentelik

- aciklama: Kendi filosunu işletmeden kendi adına taşıma yaptıran TİO, komisyoncu veya G acentesi.
- gunluk_is: Teklif, taşıyıcı ayırma, taşıma belgesi, izleme ve navlun farkı.
- ai: Müşteri mesajından taşıma türü, evrak listesi ve navlun teklifi kurar; iş emri onayla gider.

### 12.07 Depolama ve sipariş karşılama

- aciklama: Başkasının malını kabul eden, sipariş olunca toplayıp taşıyıcıya teslim eden depo.
- gunluk_is: Mal kabul, adres, sayım, toplama ve çıkış. Seferi taşıyıcı işler.
- ai: Kabul metninden stok hareketi ve siparişten toplama listesi yazar; irsaliye onaya kalır.

## Sektör ortak modüller (12.00)

Bu blok yalnız Lojistik & Taşımacılık içindir. Tüm sektörlerin ortak modülü değildir.

### 12.00.01 Sevkiyat Kartı

- oncelik: MVP
- durum: zorunlu
- aciklama: Yük/sevkiyat yaşam döngüsü: talep, yükleme, yolda, teslim; gönderici/alıcı, tonaj ve adres tek kartta.
- entegrasyonlar: yok
- ai_komutlari:
  - Bugün yüklenen 3 sevkiyatı listele
  - ABC Ltd sevkiyatını yolda yap
- ai_otomasyonu: Tetikleyici: planlanan teslim +2 saat geçti. İşlem: durumu teslim bekliyor yapıp operatöre kart aç. Çıktı: onay/erteleme seçenekli uyarı.
- mevzuat_notu: Taşıma ilişkisi TTK; uluslararasıda CMR. Belge türü alt sektöre göre.

### 12.00.02 Navlun Teklifi

- oncelik: MVP
- durum: zorunlu
- aciklama: Tonaj, güzergâh ve bekleme ile navlun taslağı; müşteriye göndermeden önce insan onayı.
- entegrasyonlar: yok
- ai_komutlari:
  - İstanbul Ankara 12 ton navlun taslağı çıkar
  - Geçen ayki ABC fiyatını bu işe kopyala
- ai_otomasyonu: Tetikleyici: yeni sevkiyat talebi. İşlem: son benzer işlerden medyan navlun öner. Çıktı: taslak teklif; otomatik gönderim yok.

### 12.00.03 U-ETDS Köprüsü

- oncelik: MVP
- durum: opsiyonel
- aciklama: Sefer, yük, şoför bildirimi için SOAP alanlarını doldurur; gönderim onaylıdır. K1/K3/C3/L1/L2/N1/N2 (TM’de C1/K2) için.
- entegrasyonlar: U-ETDS eşya SOAP WSDL (servis.turkiye.gov.tr .../uetdsesya)
- ai_komutlari:
  - 34 ABC 123 seferini U-ETDS için hazırla
  - Bugün bildirilmemiş seferleri göster
- ai_otomasyonu: Tetikleyici: sefer durumu yüklendi. İşlem: yeniSefer/yük alanlarını doldur, eksikleri işaretle. Çıktı: onaylı gönderim kuyruğu.
- mevzuat_notu: KTY md.40 f.6; Resmi Gazete 15.05.2025. P1/P2 ve salt TİO eşya U-ETDS listesinde yok. Resmi teknik doküman V3.6 ile API varlığı doğrulandı.

### 12.00.04 Teslim Kanıtı

- oncelik: MVP
- durum: zorunlu
- aciklama: Alıcı imza/foto/red ve hasar notu; faturalama için çekirdek e-Fatura sürecine veri bırakır.
- entegrasyonlar: yok
- ai_komutlari:
  - Sevkiyat 34-882 teslim kanıtını aç
  - Dün reddedilen teslimleri listele
- ai_otomasyonu: Tetikleyici: şoför teslim işaretledi. İşlem: kanıt yoksa 30 dk sonra hatırlat. Çıktı: eksik kanıt listesi.
- mevzuat_notu: Teslim ispatı; sevk e-irsaliyesi değildir.

### 12.00.05 Araç Şoför

- oncelik: MVP
- durum: opsiyonel
- aciklama: Plaka, taşıt kartı, SRC/psikoteknik bitiş ve şoför-araç eşlemesi. Personel çekirdeğinin filo genişlemesi.
- entegrasyonlar: yok
- ai_komutlari:
  - SRC si 30 günde bitecek şoförleri göster
  - 34 XYZ 45 plakasını Mehmet e ata
- ai_otomasyonu: Tetikleyici: belge bitişine 15 gün. İşlem: ilgili şoförü yeni sefere önerme. Çıktı: onay isteyen uyarı.
- mevzuat_notu: SRC/psikoteknik ve taşıt belgesi yetki türüne bağlı (K/L/N/C/P).

### 12.00.06 Hasar Dosyası

- oncelik: V2
- durum: opsiyonel
- aciklama: Hasar/kayıp dosyası, tutanak ve sigorta iletim checklisti; tazminat ödemesi AI onayı olmadan yok.
- entegrasyonlar: yok
- ai_komutlari:
  - Sevkiyat 441 için hasar dosyası aç
  - Açık hasar dosyalarını özetle
- ai_otomasyonu: Tetikleyici: POD hasarlı. İşlem: dosya + foto checklist oluştur. Çıktı: operatör onay kartı.
- mevzuat_notu: Yurt içi TTK; uluslararası CMR sorumluluk rejimi. Ev eşyası CMR kapsamı dışı.

### 12.00.07 Araç Takip

- oncelik: V2
- durum: opsiyonel
- aciklama: Harici filo takip konumunu sevkiyata bağlar; marka API iddiası doğrulanmadan bağlanır.
- entegrasyonlar: Elle veya CSV konum
- ai_komutlari:
  - 34 ABC 123 son bilinen konum
  - ETA sı geciken araçları göster
- ai_otomasyonu: Tetikleyici: ETA aşıldı. İşlem: konum yoksa manuel ETA iste. Çıktı: gecikme uyarısı.
- mevzuat_notu: Doğrulama kapanışı: Seçili filo markası yok. Konum elle veya CSV ile girilir.

## Alt sektör modülleri

## 12.01 Yurt içi karayolu yük taşımacılığı

Kendi veya sözleşmeli araçla yurt içinde komple/parça yük taşıyan K1 odaklı işletmeler.

### 12.01.01 Sefer Planı

- oncelik: MVP
- durum: zorunlu
- aciklama: Güzergâh, yükleme-boşaltma penceresi ve araç-şoför ataması; boş dönüş notu.
- entegrasyonlar: yok
- ai_komutlari:
  - Yarınki 5 seferi planla
  - 34 DEF 01 i bu sefere ata
- ai_otomasyonu: Tetikleyici: sevkiyat onaylandı. İşlem: müsait araç-şoför öner. Çıktı: atama taslağı (onaylı).
- mevzuat_notu: K1: ticari yurt içi eşya taşımacılığı.

### 12.01.02 K1 Belge

- oncelik: MVP
- durum: zorunlu
- aciklama: K1 yetki belgesi ve eki taşıt kartı süre/uyarma takibi.
- entegrasyonlar: yok
- ai_komutlari:
  - K1 belgesi ne zaman bitiyor
  - Taşıt kartı olmayan plakaları listele
- ai_otomasyonu: Tetikleyici: belge bitişine 30 gün. İşlem: ilgili plakaları sefere kapalı öner. Çıktı: yönetici uyarısı.
- mevzuat_notu: KTY K1; U-ETDS bildirimi K1 için zorunlu (12.00.03).

### 12.01.03 Yol Masrafı

- oncelik: MVP
- durum: zorunlu
- aciklama: Mazot, köprü, bekleme masraflarını sefere bağlayıp kârlılık taslağı üretir.
- entegrasyonlar: yok
- ai_komutlari:
  - Sefer 12 ye 2500 TL mazot ekle
  - Bu haftanın mazot toplamını söyle
- ai_otomasyonu: Tetikleyici: sefer kapandı. İşlem: masraf satırı yoksa hatırlat. Çıktı: eksik masraf listesi.

### 12.01.04 Takograf Uyarı

- oncelik: V2
- durum: opsiyonel
- aciklama: Planlanan sürüşe göre dinlenme/süre aşımı hatırlatması; cihaz API’si bağlanmadan çalışır.
- entegrasyonlar: Takograf süresi
- ai_komutlari:
  - Bugün dinlenme limiti yaklaşan şoförler
- ai_otomasyonu: Tetikleyici: planlanan sürüş eşiği aşıldı. İşlem: uyarı kartı aç. Çıktı: şoför ve operatör bildirimi.
- mevzuat_notu: Takograf yükümlülüğü araç sınıfına bağlı; entegrasyon doğrulanmadı. Doğrulama kapanışı: https://www.dijitaltakograf.gov.tr/ bu turda 500 verdi. Cihaz API’si seçilmedi. Süre hatırlatması panelde.

### 12.01.05 Taşıma İrsaliye

- oncelik: V2
- durum: opsiyonel
- aciklama: VUK taşıma irsaliyesi alanları; sevk e-irsaliyesi ile karıştırılmaz.
- entegrasyonlar: yok
- ai_komutlari:
  - Sefer 8 için taşıma irsaliyesi taslağı
  - Bugün irsaliyesiz kalkan seferler
- ai_otomasyonu: Tetikleyici: yükleme onayı. İşlem: taşıma irsaliyesi taslağı. Çıktı: PDF/yazdırma.
- mevzuat_notu: Taşımacı: taşıma irsaliyesi. Sevk/e-irsaliye malı gönderen mükellefe (509 VUK); ciro/sektör eşiği taşımacıya otomatik uygulanmaz.

## 12.02 Uluslararası karayolu yük taşımacılığı

Sınır ötesi karayolu yük seferi; belge fiilen L2 (eski C2 dönüşümü).

### 12.02.01 CMR Belgesi

- oncelik: MVP
- durum: zorunlu
- aciklama: CMR taşıma senedi alanları ve ihtirazi kayıt; ev eşyası taşınması CMR dışı.
- entegrasyonlar: yok
- ai_komutlari:
  - TR DE seferi için CMR taslağı
  - CMR ye ihtirazi kayıt ekle
- ai_otomasyonu: Tetikleyici: ülke dışı sevkiyat oluşturuldu. İşlem: CMR taslak doldur. Çıktı: onay sonrası PDF.
- mevzuat_notu: CMR md.1; ev eşyası, posta, cenaze istisna. Belgesizlik sözleşmeyi düşürmez.

### 12.02.02 L2 Belge

- oncelik: MVP
- durum: zorunlu
- aciklama: L2 yetki ve taşıt belgesi takibi; U-ETDS L2 yükümlülüğü.
- entegrasyonlar: yok
- ai_komutlari:
  - L2 geçerlilik tarihini göster
  - Taşıt belgesine eklenecek plakalar
- ai_otomasyonu: Tetikleyici: L2 bitişine 45 gün. İşlem: yönetici uyarısı. Çıktı: yenileme kartı.
- mevzuat_notu: RG 14.01.2023: C2 verilmiyor, mevcutlar L2. U-ETDS L2 zorunlu.

### 12.02.03 Transit Dosya

- oncelik: MVP
- durum: zorunlu
- aciklama: TIR karne / NCTS / geçiş izni checklist; hangisinin kullanılacağı güzergâha bağlı.
- entegrasyonlar: TOBB TIR portalı
- ai_komutlari:
  - Bu seferde TIR karne durumu ne
  - Almanya geçiş izni eksik mi
- ai_otomasyonu: Tetikleyici: sefer gümrük öncesi. İşlem: eksik transit belgesi listesi. Çıktı: checklist.
- mevzuat_notu: TIR gümrük transit; CMR sözleşme belgesi. AB içi transitte NCTS yaygın. Doğrulama kapanışı: https://tir.tobb.org.tr/ bu turda 500 verdi. Portal API’si okunamadı. Evrak listesi panelde.

### 12.02.04 Ro-Ro Slot

- oncelik: V2
- durum: opsiyonel
- aciklama: Feribot/Ro-Ro rezervasyonunu sevkiyat ETA’sına bağlar.
- entegrasyonlar: Hat kaydı
- ai_komutlari:
  - Trieste slotunu bu sevkiyata bağla
- ai_otomasyonu: Tetikleyici: slot saatine 24 saat. İşlem: hatırlatma. Çıktı: operatör bildirimi.
- mevzuat_notu: Doğrulama kapanışı: Seçili hat yok. Slot elle girilir.

### 12.02.05 Geçiş İzni

- oncelik: V2
- durum: opsiyonel
- aciklama: Ülke geçiş belgesi stok ve kullanım kaydı.
- entegrasyonlar: yok
- ai_komutlari:
  - Romanya geçiş izni kalan adet
- ai_otomasyonu: Tetikleyici: stok 2 altına düştü. İşlem: uyarı. Çıktı: tedarik notu.
- mevzuat_notu: İkili/çok taraflı geçiş izin rejimleri güzergâha göre değişir.

## 12.03 Nakliyat ambarı

Parça yükü ambarda toplayıp hat aracıyla dağıtan N1/N2 işletmeleri.

### 12.03.01 Parsiyel Toplama

- oncelik: MVP
- durum: zorunlu
- aciklama: Parça yük kabul, etiketleme ve hat aracına konsolidasyon.
- entegrasyonlar: yok
- ai_komutlari:
  - Ankara hattına 4 parça ekle
  - Bugün kabul edilen parçaları listele
- ai_otomasyonu: Tetikleyici: ambar kabulü. İşlem: hedef hat öner. Çıktı: tasnif listesi.
- mevzuat_notu: N1 il içi, N2 iller arası nakliyat ambarı; U-ETDS N1/N2.

### 12.03.02 Hat Seferi

- oncelik: MVP
- durum: zorunlu
- aciklama: Hat aracı kalkış, doluluk ve varış ambarında aktarma.
- entegrasyonlar: U-ETDS eşya SOAP
- ai_komutlari:
  - İstanbul Ankara hattı doluluk oranı
  - Hat 3 ü kalkışa kapat
- ai_otomasyonu: Tetikleyici: kalkışa 2 saat. İşlem: U-ETDS taslak + eksik yük uyarısı. Çıktı: onay kuyruğu.
- mevzuat_notu: N türü için U-ETDS eşya bildirimi zorunlu.

### 12.03.03 Ambar Stok

- oncelik: MVP
- durum: zorunlu
- aciklama: Kapalı ambar giriş-çıkış, göz/yer ve bekleyen parça arama.
- entegrasyonlar: yok
- ai_komutlari:
  - Raf A-12 de ne var
  - 3 gündür bekleyen parçalar
- ai_otomasyonu: Tetikleyici: bekleme 72 saati aştı. İşlem: müşteri arama listesi. Çıktı: operatör kartı.
- mevzuat_notu: N1 ≥75 m², N2 ≥150 m² kapalı ambar şartı (KTY md.14).

### 12.03.04 G1 Acente

- oncelik: V2
- durum: opsiyonel
- aciklama: Başka N belgesi adına yük kabul eden G1 acente sözleşmeleri.
- entegrasyonlar: yok
- ai_komutlari:
  - G1 sözleşmeli ambarları listele
- ai_otomasyonu: Tetikleyici: sözleşme bitişine 30 gün. İşlem: yenileme uyarısı. Çıktı: yönetici kartı.
- mevzuat_notu: G1 acentelik ≠ N işletmeciliği.

### 12.03.05 N Belge

- oncelik: V2
- durum: zorunlu
- aciklama: N1/N2 süre ve şube alan uygunluk notu.
- entegrasyonlar: yok
- ai_komutlari:
  - N2 belgesi bitiş tarihi
  - Şube alan uyarısı var mı
- ai_otomasyonu: Tetikleyici: belge bitişine 30 gün. İşlem: uyarı. Çıktı: yönetici bildirimi.
- mevzuat_notu: KTY md.14 N1/N2 asgari taşıt ve m² şartları.

## 12.04 Şehir içi kurye ve dağıtım

Şehir içi çok duraklı küçük paket/kurye; P1 (ve koşullu P2) odaklı.

### 12.04.01 Durak Rotası

- oncelik: MVP
- durum: zorunlu
- aciklama: Çok duraklı teslim sırası; kurye gönderisi boyutu notu.
- entegrasyonlar: Google Routes API
- ai_komutlari:
  - Bugünkü 18 durağı sırala
  - Öğleden sonra rotayı yeniden kur
- ai_otomasyonu: Tetikleyici: sabah planı. İşlem: adres sırası taslağı. Çıktı: kurye listesi (onaylı).
- mevzuat_notu: RG 15.05.2025: P kurye (≤30 kg / 300 dm³ tanımı). U-ETDS eşya zorunlu listesinde P yok. Google Routes API (Compute Routes / Route Matrix) kamuya açık dokümanda. Faturalı API anahtarı gerekir. P1 kurye tanımı ve U-ETDS listesinde P olmaması ayrı mevzuat notudur.

### 12.04.02 Kurye Atama

- oncelik: MVP
- durum: zorunlu
- aciklama: Bölge ve kapasiteye göre kurye/araç ataması. Personel çekirdeği genişlemesi.
- entegrasyonlar: yok
- ai_komutlari:
  - Kadıköy bölgesine 2 kurye ata
  - En az yüklü kuryeyi öner
- ai_otomasyonu: Tetikleyici: yeni paket. İşlem: en az yüklü uygun kuryeyi öner. Çıktı: atama onayı.
- mevzuat_notu: P1 asgari 5 özmal; P1* ≤3 taşıt esnaf istisnası.

### 12.04.03 Canlı Teslim

- oncelik: MVP
- durum: zorunlu
- aciklama: Teslim kodu/link, red ve iade akışı.
- entegrasyonlar: WhatsApp Cloud API
- ai_komutlari:
  - 8841 için teslim kodu gönder
  - Bugünkü iade kuyruğunu aç
- ai_otomasyonu: Tetikleyici: kurye adreste. İşlem: tek kullanımlık kod taslağı. Çıktı: gönderim onayı.
- mevzuat_notu: Alıcı iletişim verisi amaçla sınırlı; genel KVKK şablonu değil. WhatsApp Cloud API dokümanı bu oturumda açıldı (Graph API, şablon onayı, işletme doğrulama). SMS sağlayıcısı seçilmediği için dogrulanmali true kaldı. Doğrulama kapanışı: WhatsApp Cloud API dokümanı açıldı (Graph API, şablon onayı, işletme doğrulama). SMS sağlayıcısı seçilmedi. Varış metni şablon taslağıdır, gönderim onayla gider.

### 12.04.04 P Belge

- oncelik: V2
- durum: zorunlu
- aciklama: P1/P2 geçerlilik ve özmal taşıt sayısı kontrolü.
- entegrasyonlar: yok
- ai_komutlari:
  - P1 taşıt sayısı eksiği var mı
- ai_otomasyonu: Tetikleyici: taşıt kaydı silindi. İşlem: asgari kapasite kontrolü. Çıktı: uyarı.
- mevzuat_notu: P1/P2 KTY md.14; eski dağıtım P belgeleri M1/M2 ye dönüşmüş olabilir — kurye tanımı 2025.

### 12.04.05 Yoğunluk Paneli

- oncelik: V2
- durum: opsiyonel
- aciklama: Saat dilimine göre başarısız teslim ve neden özeti.
- entegrasyonlar: yok
- ai_komutlari:
  - Dün başarısız teslim nedenlerini özetle
- ai_otomasyonu: Tetikleyici: gün sonu. İşlem: neden dağılımı. Çıktı: rapor taslağı.

## 12.05 Ev ve büro taşımacılığı

Ev/büro taşınma eşyası; yurt içi K3, uluslararası C3.

### 12.05.01 Keşif Randevu

- oncelik: MVP
- durum: zorunlu
- aciklama: Keşif günü, kat, asansör, m²; teklife girdi. CRM çekirdeğine iş akışı bağlar.
- entegrasyonlar: yok
- ai_komutlari:
  - Cumartesi keşiflerini listele
  - Bu keşfi tamamlandı yap
- ai_otomasyonu: Tetikleyici: keşif +1 gün teklif yok. İşlem: hatırlatma. Çıktı: satıcı kartı.

### 12.05.02 Eşya Envanter

- oncelik: MVP
- durum: zorunlu
- aciklama: Oda bazlı eşya listesi, kırılgan ve demontaj notları.
- entegrasyonlar: yok
- ai_komutlari:
  - Salon envanterine piyano ekle
  - Fotoğrafı eksik odaları göster
- ai_otomasyonu: Tetikleyici: keşif kapandı. İşlem: eksik oda checklist. Çıktı: tamamla uyarısı.
- mevzuat_notu: Uluslararası ev eşyası CMR kapsamı dışında (CMR md.1).

### 12.05.03 Ekip Atama

- oncelik: MVP
- durum: zorunlu
- aciklama: Taşınma günü kamyon, ekip ve paketleme malzemesi ataması.
- entegrasyonlar: yok
- ai_komutlari:
  - 15 Mayıs taşınmasına 3 kişi ata
  - Paketleme malzemesi eksiği var mı
- ai_otomasyonu: Tetikleyici: kapora alındı. İşlem: müsait ekip öner. Çıktı: onaylı atama.
- mevzuat_notu: K3 yurt içi, C3 yurt içi+uluslararası taşınma; U-ETDS K3/C3.

### 12.05.04 K3 C3 Belge

- oncelik: V2
- durum: zorunlu
- aciklama: İşin yurt içi/uluslararası olmasına göre K3 veya C3 yönlendirmesi.
- entegrasyonlar: yok
- ai_komutlari:
  - Bu iş için K3 mü C3 mü gerekir
- ai_otomasyonu: Tetikleyici: varış ülkesi TR dışı. İşlem: C3 + CMR istisna notu. Çıktı: belge uyarısı.
- mevzuat_notu: KTY K3/C3 tanımları; U-ETDS yükümlülüğü.

### 12.05.05 Sigorta Teklif

- oncelik: V2
- durum: opsiyonel
- aciklama: Beyan değerine göre nakliyat sigortası maddesini teklife ekleme hatırlatması.
- entegrasyonlar: Sigorta kaydı
- ai_komutlari:
  - Bu taşınma için sigorta tutarı öner
- ai_otomasyonu: Tetikleyici: envanter değeri eşiği aştı. İşlem: teklife sigorta maddesi ekle. Çıktı: onaylı teklif satırı.
- mevzuat_notu: Doğrulama kapanışı: https://www.sbm.org.tr/ açıldı. Poliçe ve hasar sorguları sigorta ekosistemine ait. Nakliyeciye açık teklif API’si sayfada yok. Teklif kaydı elle.

## 12.06 Taşıma organizatörlüğü ve acentelik

Filo işletmeden taşımayı organize eden TİO ve N acenteliği (G1) işletmeleri.

### 12.06.01 Taşıyıcı Havuz

- oncelik: MVP
- durum: zorunlu
- aciklama: Alt taşıyıcı yetki belgesi, fiyat ve performans havuzu.
- entegrasyonlar: yok
- ai_komutlari:
  - İzmir e müsait K1 taşıyıcıları öner
  - XYZ Nakliyat ı kara listeye öner
- ai_otomasyonu: Tetikleyici: yeni booking. İşlem: güzergâh ve puanla öner. Çıktı: seçim onayı.
- mevzuat_notu: TİO kendi namına fatura keser, taşımayı yaptırır.

### 12.06.02 Booking Emri

- oncelik: MVP
- durum: zorunlu
- aciklama: Müşteri emrini taşıyıcı iş emrine çevirir; alış/satış navlun marjı tutar.
- entegrasyonlar: yok
- ai_komutlari:
  - Booking 220 yi Ahmet Lojistik e ver
  - Açık bookingleri listele
- ai_otomasyonu: Tetikleyici: müşteri onayı. İşlem: iş emri taslağı. Çıktı: taşıyıcıya gönderim onayı.
- mevzuat_notu: U-ETDS fiili taşımayı yapan yetki belgesi sahibinde; salt TİO eşya listesinde yok.

### 12.06.03 TİO Belge

- oncelik: MVP
- durum: zorunlu
- aciklama: TİO belgesi (eski R1/R2) ve G1 acente ayrımı.
- entegrasyonlar: yok
- ai_komutlari:
  - TİO belgesi bitiş tarihi
  - Bu iş G1 mi TİO mu
- ai_otomasyonu: Tetikleyici: belge bitişine 30 gün. İşlem: uyarı. Çıktı: yönetici kartı.
- mevzuat_notu: Taşıma İşleri Organizatörlüğü Yönetmeliği; R türü TİO ya dönüşmüş. G1 N acenteliği.

### 12.06.04 Multimodal Plan

- oncelik: V2
- durum: opsiyonel
- aciklama: Kara + deniz/hava bacak checklisti.
- entegrasyonlar: Hat planı
- ai_komutlari:
  - Mersin liman bacağını plana ekle
- ai_otomasyonu: Tetikleyici: liman ETA. İşlem: sonraki bacak hatırlatması. Çıktı: plan kartı.
- mevzuat_notu: TİO kombine/intermodal faaliyet tanımı. Doğrulama kapanışı: Seçili liman veya hat yok. Plan elle tutulur.

### 12.06.05 Marj Paneli

- oncelik: V2
- durum: opsiyonel
- aciklama: Alış navlun ile satış navlun farkı; zararlı iş uyarısı.
- entegrasyonlar: yok
- ai_komutlari:
  - Bu ay negatif marjlı işleri göster
- ai_otomasyonu: Tetikleyici: iş kapandı. İşlem: marj < 0 ise uyarı. Çıktı: rapor satırı.

## 12.07 Depolama ve sipariş karşılama

Başkasının malını depolayıp sipariş karşılayan (fulfillment) işletmeler; dağıtım varsa L belgesi gündeme gelir.

### 12.07.01 Lokasyon Stok

- oncelik: MVP
- durum: zorunlu
- aciklama: Mal sahibi, SKU ve göz/adres bazlı stok; kabul ve sayım.
- entegrasyonlar: yok
- ai_komutlari:
  - X markanın stokunu göster
  - Sayım farkı olan gözleri listele
- ai_otomasyonu: Tetikleyici: günlük sayım kapandı. İşlem: fark listesi. Çıktı: mutabakat taslağı.
- mevzuat_notu: Salt depolamada U-ETDS yok. Dağıtımı kendisi yapıyorsa L1/L2 veya taşımacı belgesi ayrı değerlendirilir.

### 12.07.02 Pick Pack

- oncelik: MVP
- durum: zorunlu
- aciklama: Sipariş toplama, paketleme ve sevke hazır etme kuyruğu.
- entegrasyonlar: Mikro API
- ai_komutlari:
  - Bugün 40 siparişi kuyruğa al
  - Eksik stoklu siparişleri göster
- ai_otomasyonu: Tetikleyici: sipariş onaylandı. İşlem: pick listesi üret. Çıktı: toplayıcı sırası.
- mevzuat_notu: Doğrulama kapanışı: Mikro API açıldı: DahiliStokHareketKaydetV2. Pazaryeri seçilmedi. Stok hareketi Mikro hesabıyla, onayla yazılır.

### 12.07.03 Mal Sahibi Hesap

- oncelik: MVP
- durum: zorunlu
- aciklama: Depolama ve işlem ücretleri; dönem mutabakatı çekirdek e-Faturaya el verir.
- entegrasyonlar: yok
- ai_komutlari:
  - Mart mutabakatını hazırla
  - Faturalanacak bekleyen işlemler
- ai_otomasyonu: Tetikleyici: ay sonu. İşlem: işlem dökümü. Çıktı: onaylı mutabakat taslağı.

### 12.07.04 Sevk İrsaliye

- oncelik: V2
- durum: opsiyonel
- aciklama: Mal çıkışında sevk/e-irsaliye yükümlüsünü (mal sahibi vs lojistik merkez) ayırt eden checklist.
- entegrasyonlar: Mikro e-İrsaliye API
- ai_komutlari:
  - Bu çıkışta irsaliyeyi kim düzenlemeli
- ai_otomasyonu: Tetikleyici: mal çıkış emri. İşlem: rol checklist. Çıktı: uyarı kartı.
- mevzuat_notu: 509 VUK e-irsaliye sevk irsaliyesidir; e-Fatura + 10M TL (2021+) veya sektör listeleri. Taşımacının taşıma irsaliyesi ayrı belgedir. Lojistik merkez senaryoları GİB kılavuzuna göre değişir. Doğrulama kapanışı: Mikro API açıldı: IrsaliyeKaydetV2 ve EIrsaliyeGonderV2. Ham GİB ucu KOBİ’ye açık değil. Taslak panelde, GİB gönderimi Mikro hesabı ve onayla.

### 12.07.05 L Belge Notu

- oncelik: V2
- durum: opsiyonel
- aciklama: Depo + dağıtım birlikteyse L1/L2 hatırlatması.
- entegrasyonlar: yok
- ai_komutlari:
  - Faaliyetimiz L1 mi N mi görünüyor
- ai_otomasyonu: Tetikleyici: ilk kendi araçlı dağıtım kaydı. İşlem: belge sorusu aç. Çıktı: yapılandırma kartı.
- mevzuat_notu: L1 yurt içi, L2 yurt içi+uluslararası lojistik işletmeciliği; U-ETDS L1/L2.

## Sayım

- sektor_ortak: 7
- alt_sektor: 7
- modul: 42
- mvp: 26

## Kaynaklar

- Karayolu Taşıma Yönetmeliği: https://www.mevzuat.gov.tr/MevzuatMetin/yonetmelik/7.5.24299.pdf
- U-ETDS eşya: https://uetds.uab.gov.tr/esya
- U-ETDS teknik doküman: https://uetds.uab.gov.tr/teknik-dokuman
- TİO Yönetmeliği: https://www.mevzuat.gov.tr/MevzuatMetin/yonetmelik/7.5.39686.pdf
- UTİKAD 2024 raporu: https://www.utikad.org.tr/images/HizmetRapor/utikadlojistiksektoruraporu2024-9911.pdf
