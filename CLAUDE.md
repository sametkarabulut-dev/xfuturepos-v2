# Xfuturepos – Sektör İhtiyaç Araştırması (Obsidian Kasası)

## Bağlam
- Xfuturepos sıfırdan yeniden yapılıyor. Satışta ürün yok; her şey plan aşamasında.
- Amaç: (1) satış için sektör ihtiyaç haritası, (2) yatırımcıya sunulacak rapor.
- Pazar: Türkiye geneli KOBİ (yaklaşık 1–50 çalışan bandı).
- Bu klasör Obsidian kasasıdır. Tüm notlar Türkçe, Markdown. HTML ve JSON kaynak değildir.

## KAPSAM (kesin kural)
Yalnızca şu 6 sektör. Dışına ÇIKMA:
09 Emlak & Gayrimenkul · 10 İnşaat & Yapı · 12 Lojistik & Taşımacılık · 13 Üretim & İmalat · 15 Teknoloji Medya & Ajans · 16 Etkinlik & Organizasyon
Sınırda kalan alt türleri kendin ekleme; `onay-bekliyor` işaretle ve sor.

## Okuma sırası
1. `00 Pano/Ana Pano.md` · `Ana Ağaç` · `Araç Kutusu` · `Alan Sözlüğü`
2. `04 Modüller/` — çekirdek ve sektörel araçlar
3. `01 Sektörler/<sektör>.md`
4. `02 İşletmeler/<sektör>/…` — dal + işletme (Parçalar)
5. `00 Pano/Parça Eşlemesi – …` · `Doğrulama – …` · `09 Mimari/`
6. Gerekirse `03 İhtiyaçlar/`, `07 Fonksiyonlar/`, `05 Rakipler/`, `06 Kaynaklar/`

## Çalışma kuralları
- Gereksiz soru sorma. Karar kullanıcıya aitse sor.
- Detaylı ama sade yaz: kısa cümleler, madde işaretleri, tablolar.
- Rakam ve iddialar için kaynak göster. Tahmin ise "tahmin" veya "bulunamadı".
- Modül kartında `oncelik` yalnız MVP|V2; `durum` yalnız zorunlu|opsiyonel.
- Ödeme, bağlayıcı sözleşme, resmi başvuru, müşteri mesajı onay kuyruğundan çıkar.
- İşletme notunda fiyat/iş modeli önerisi yazma.
- Parça derecesi: şart · olmalı · iyi olur.

## Kasa yapısı
```
00 Pano/        Ana Pano, Alan Sözlüğü, Araç Kutusu, Bases, Ağaçlar/, Parça Eşlemesi, Doğrulama, Araştırma Planı
01 Sektörler/   6 sektör notu
02 İşletmeler/  sektör → dal → işletme türü
03 İhtiyaçlar/  her ihtiyaç = 1 not
04 Modüller/    her araç = 1 not
05 Rakipler/    her rakip = 1 not
06 Kaynaklar/   sektör kaynak listeleri
07 Fonksiyonlar/ her fonksiyon = 1 not
08 Arşiv/       eski notlar (git dışı)
09 Mimari/      sistem mimarisi raporu
99 Şablonlar/   şablonlar
```

## Ürün ilkesi
- İşletmelere **araç** veriyoruz. Ortak çekirdek tüm sektörlerde bir kez durur.
- İşletme türü = araçların birleşimi (Parçalar).
- Ağır resmi entegrasyon (açık API yoksa) panel kaydı + kullanıcı girişi.

## Alan sözlüğü
Ayrıntı: [[Alan Sözlüğü]]. Öncelik: `((pazar+odeme+rekabet+kolaylik+aciliyet)/5).toFixed(1)`
