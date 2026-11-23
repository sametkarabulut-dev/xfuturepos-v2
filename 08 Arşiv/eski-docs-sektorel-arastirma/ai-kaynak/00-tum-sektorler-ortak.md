---
tip: ortak
katman: 0
durum: tamamlandi
kural: Bu dosyadaki modüller her sektörde bir kez vardır. Sektör dosyaları bunları yeniden tanımlamaz.
---

# 00 Tüm sektörlerin ortak modülleri

Her KOBİ panelinde aynı yedi modül durur. Sektör dosyasındaki `09.00`, `10.00` gibi kodlar yalnız o sektörün ortak işidir. Aşağıdakiler sektör ayrımı yapmaz.

Yüksek etkili işlem onaysız gitmez: tahsilat ve ödeme, bağlayıcı sözleşme, resmi başvuru, müşteriye giden mesaj.

## Liste

| id | ad | oncelik | durum |
| --- | --- | --- | --- |
| 00.01 | Muhasebe ve Gelir-Gider | MVP | zorunlu |
| 00.02 | e-Fatura ve e-Arşiv | MVP | zorunlu |
| 00.03 | CRM | MVP | zorunlu |
| 00.04 | Personel ve Vardiya | MVP | zorunlu |
| 00.05 | Raporlar | MVP | zorunlu |
| 00.06 | AI Asistan | MVP | zorunlu |
| 00.07 | Ayarlar | MVP | zorunlu |

## 00.01 Muhasebe ve Gelir-Gider

- oncelik: MVP
- durum: zorunlu
- aciklama: Gelir, gider, cari, kasa ve banka hareketi. Sektör ekranı kendi belgesini üretir; para kaydı buraya düşer.
- ai_komutlari:
  - "Bu ayın gelir ve giderini göster"
  - "Vadesi geçmiş carileri listele"
- ai_otomasyonu: Tetikleyici yeni tahsilat veya gider fişi. İşlem cari bakiyesini günceller. Çıktı kasa hareketi. Ödeme ve mahsup insan onayındadır.
- entegrasyonlar: Dekont ile mutabakat. Tek banka API’si seçilmedi.
- mevzuat_notu: Resmi defter ve beyanname bu modülün işi değildir. Kayıt panelde durur.

## 00.02 e-Fatura ve e-Arşiv

- oncelik: MVP
- durum: zorunlu
- aciklama: Satış belgesinin taslağı. Gönderim özel entegratör hesabıyla ve onayla olur. Ham GİB ucu KOBİ paneline açık değildir.
- ai_komutlari:
  - "Bu satış için fatura taslağı hazırla"
  - "Gönderilmemiş e-Arşiv taslaklarını göster"
- ai_otomasyonu: Tetikleyici onaylı satış. İşlem kalem, vergi ve cariyi taslağa yazar. Çıktı inceleme kuyruğu. Gönderim yok.
- entegrasyonlar: Mikro e-belge uçları doğrulandı (FaturaKaydetV2, EIrsaliyeGonderV2). Logo ve Nebim listede yok.
- mevzuat_notu: e-İrsaliye her işletmeye otomatik değildir. Kapsam sektör notundaki VUK 509 cümlesindedir. Kesim onayla gider.

## 00.03 CRM

- oncelik: MVP
- durum: zorunlu
- aciklama: Kişi ve firma kartı, iletişim, not ve sektör belgesine bağ. Müşteri, malik, hasta, tedarikçi aynı kart ailesindedir. Sektör kendi alanını karta ekler.
- ai_komutlari:
  - "Bu müşterinin açık işlerini göster"
  - "Son 30 günde konuşulmayan carileri listele"
- ai_otomasyonu: Tetikleyici yeni kart veya gelen not. İşlem eksik telefon, vergi no ve açık işi işaretler. Çıktı tamamlanacak alan listesi. Müşteriye mesaj gitmez.
- entegrasyonlar: Yok.
- mevzuat_notu: Kart kişiye aitse aydınlatma metni ayarlardan gelir. Mesaj onayı 00.06 kuralındadır.

## 00.04 Personel ve Vardiya

- oncelik: MVP
- durum: zorunlu
- aciklama: Personel kartı, vardiya ve puantaj günü. Bordro ve SGK bildirimi bu modülde kesilmez.
- ai_komutlari:
  - "Yarının vardiyasını göster"
  - "Bugün gelmeyen personeli listele"
- ai_otomasyonu: Tetikleyici vardiya günü. İşlem plan ile yoklamayı karşılaştırır. Çıktı eksik yoklama listesi. İşe giriş bildirimi kullanıcıdadır.
- entegrasyonlar: PDKS markası seçilmedi. Yoklama panelden girilir.
- mevzuat_notu: İSG-KATİP ve SGK ekranları kurumdadır. Panel kayıt tutar.

## 00.05 Raporlar

- oncelik: MVP
- durum: zorunlu
- aciklama: Ciro, tahsilat, açık iş ve personel günü. Sektör raporu bu iskelete kendi sayısını ekler.
- ai_komutlari:
  - "Bu haftanın özetini yaz"
  - "Geçen aya göre tahsilatı karşılaştır"
- ai_otomasyonu: Tetikleyici gün kapanışı. İşlem 00.01 ve açık işlerden özet taslağı kurar. Çıktı yönetici notu. Dışarı gönderim yok.
- entegrasyonlar: Yok.
- mevzuat_notu: Yok.

## 00.06 AI Asistan

- oncelik: MVP
- durum: zorunlu
- aciklama: Sektör modülündeki komutları çalıştırır. Taslak üretir. Tahsilat, sözleşme, resmi başvuru ve müşteri mesajını kendisi bitirmez.
- ai_komutlari:
  - "Bu kayıttan taslak çıkar"
  - "Eksik alanı söyle"
- ai_otomasyonu: Tetikleyici kullanıcı komutu veya modüldeki tetikleyici. İşlem ilgili modülün kuralını uygular. Çıktı onay kuyruğu.
- entegrasyonlar: Yok.
- mevzuat_notu: Onaysız müşteri mesajı, ödeme çağrısı ve kurum gönderimi yasaktır.

## 00.07 Ayarlar

- oncelik: MVP
- durum: zorunlu
- aciklama: Firma, şube, vergi, kullanıcı, yetki, belge şablonu ve entegrasyon anahtarı. Sektör anahtarı burada durur, sektör modülünde kopyalanmaz.
- ai_komutlari:
  - "Eksik firma ayarını göster"
  - "Bu kullanıcının yetkisini söyle"
- ai_otomasyonu: Tetikleyici yeni firma. İşlem vergi no, adres ve e-belge hesabı boşsa görev açar. Çıktı kurulum listesi.
- entegrasyonlar: Entegrasyon anahtarları bu ekranda tutulur.
- mevzuat_notu: Anahtar ve şifre sohbet metnine yazılmaz.
