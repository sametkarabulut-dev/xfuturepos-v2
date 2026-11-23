---
tip: modul
kod: "09.03.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Genel Kurul

> Kod `09.03.02` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Toplantı çağrısı, gündem, karar ve tutanak arşivi.

## Özellikler
### MVP
- Son kurul kararlarını özetle
- Yönetim planı değişiklik gündemi hazırla
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: toplantı tarihi −14 gün → İşlem: çağrı/gündem taslağı → Çıktı: yönetici onaylı gönderim kuyruğu

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- KMK m.27–34; toplu yapı yönetim planı oy oranı 7579 ile güncellendi.

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
