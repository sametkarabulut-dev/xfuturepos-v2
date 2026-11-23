# Xfuturepos – Sektör İhtiyaç Araştırması (Obsidian Kasası)

## Bağlam
- Xfuturepos sıfırdan yeniden yapılıyor. Satışta ürün yok; her şey plan aşamasında.
- Amaç: (1) satış için sektör ihtiyaç haritası, (2) yatırımcıya sunulacak rapor.
- Pazar: Türkiye geneli KOBİ (yaklaşık 1–50 çalışan bandı).
- Bu klasör Obsidian kasasıdır. Tüm notlar Türkçe, Markdown. HTML ve JSON kaynak değildir.

## KAPSAM (kesin kural)
Yalnızca şu 6 sektör. Dışına ÇIKMA:
09 Emlak & Gayrimenkul · 10 İnşaat & Yapı · 12 Lojistik & Taşımacılık · 13 Üretim & İmalat · 15 Teknoloji Medya & Ajans · 16 Etkinlik & Organizasyon

## Okuma sırası
1. `04 Modüller/` — çekirdek araçlar (Muhasebe, e-Fatura, CRM, Personel, Raporlar, AI Asistan, Ayarlar)
2. `01 Sektörler/<sektör>.md` — özet, dallar, araç matrisi, yasal, pazar, rakip
3. `02 İşletmeler/<sektör>/…` — dal ve işletme türü notları
4. Gerekirse `03 İhtiyaçlar/`, `07 Fonksiyonlar/`, `05 Rakipler/`, `06 Kaynaklar/`

## Çalışma kuralları
- Gereksiz soru sorma. Sadece karar kullanıcıya aitse sor.
- Detaylı ama sade yaz: kısa cümleler, madde işaretleri, tablolar.
- Rakam ve iddialar için kaynak göster. Tahmin ise "tahmin" veya "bulunamadı" yaz.
- `oncelik` yalnız MVP veya V2; `durum` yalnız zorunlu veya opsiyonel (modül kartlarında).
- Ödeme, bağlayıcı sözleşme, resmi başvuru ve müşteri mesajı onay kuyruğundan çıkar.
- `[[wiki link]]` Obsidian bağlantısıdır; AI bunu özellik/modül/işletme adı olarak okur.

## Kasa yapısı
```
00 Pano/        Ana Pano, Alan Sözlüğü, Bases
01 Sektörler/   6 sektör notu
02 İşletmeler/  sektör → dal → işletme türü
03 İhtiyaçlar/  her ihtiyaç = 1 not
04 Modüller/    her çözüm araç = 1 not
05 Rakipler/    her rakip = 1 not
06 Kaynaklar/   sektör kaynak listeleri
07 Fonksiyonlar/ her fonksiyon = 1 not
08 Arşiv/       eski notlar (git dışı)
99 Şablonlar/   şablonlar
```

## Ürün ilkesi
- İşletmelere **araç** veriyoruz. Ortak çekirdek tüm sektörlerde bir kez durur.
- Sektör ortak (`SS.00`) ve alt sektör (`SS.AA`) araçları o sektörün dosya ağacında durur.
- İşletme türü = araçların birleşimi. Tek türe özgü ağır resmi entegrasyon (açık API yoksa) panel kaydı + kullanıcı girişi ile çözülür.

## Alan sözlüğü (frontmatter)
Ortak: `tip` (sektor | isletme | dal | ihtiyac | modul | rakip | fonksiyon | kaynak), `durum` (taslak | arastiriliyor | tamamlandi | onay-bekliyor)

İşletme: `sektor`, `dal`, `pazar_puani`, `odeme_puani`, `rekabet_puani`, `kolaylik_puani`, `aciliyet_puani`, `ihtiyaclar`, `moduller`, `rakipler`, `fonksiyonlar`, `fiyat_araligi`, `is_modeli`, `nace`, `olcek`

Öncelik formülü: `((pazar+odeme+rekabet+kolaylik+aciliyet)/5).toFixed(1)`
