---
tip: modul
kod: "15.07.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Lisans Takibi

> Kod `15.07.04` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Paket yazılım lisans ve iş ortaklığı kaydı.

## Özellikler
### MVP
- Lisansı biten müşterileri listele
- Lisans durumunu özetle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: aylık. İşlem: lisans bitişlerini tara. Çıktı: yenilenecek lisans listesi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Elle lisans tarihi

## Mevzuat
- Logo/iş ortağı API entegrasyonu bu turda doğrulanmadı. Doğrulama kapanışı: Logo iş ortağı lisans API’si bu turda açılmadı. Lisans bitişi elle tutulur.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[15 Teknoloji Medya & Ajans]]:** sektör/alt araç

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
