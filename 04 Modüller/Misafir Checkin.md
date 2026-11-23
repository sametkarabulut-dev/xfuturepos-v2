---
tip: modul
kod: "09.05.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Misafir Checkin

> Kod `09.05.03` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Kimlik/pasaport kaydı, giriş-çıkış ve ev kuralları onayı.

## Özellikler
### MVP
- Bugün check-in listesini getir
- Eksik kimlik kaydı olanları göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: check-in −24 sa → İşlem: eksik belge uyarısı → Çıktı: host görev kartı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Panel kaydı

## Mevzuat
- İzin belgesi sahibi yükümlülükleri; kolluk/bildirim entegrasyonu ayrıca doğrulanmalı. Doğrulama kapanışı: Harici API bağlanmadı. Kimlik ve giriş kaydı panelde durur. Kolluk bildirimi tesisin kendi ekranında, onayla kalır.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[09 Emlak & Gayrimenkul]]:** sektör/alt araç

## Kullanan işletme türleri
```base
filters:
  and:
    - 'tip == "isletme"'
    - file.hasLink(this.file)
views:
  - type: table
    name: Kullanan işletme türleri
```
