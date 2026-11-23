---
tip: modul
kod: "16.01.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Mekân lisans

> Kod `16.01.03` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- UMK (MSF) + müzik yayın izni + işyeri ruhsatı son tarih takibi.

## Özellikler
### MVP
- Müzik yayın izni bitiş?
- Bu ay yenilenecek belgeler?
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- İzin −60 gün kala yenileme görevi açar.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- FSEK m.41; MSF UMK; ÇGK Yönetmeliği müzik yayın izni. Yıllık UMK, davetli/biletli etkinliği otomatik kapsamaz.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[16 Etkinlik & Organizasyon]]:** sektör/alt araç

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
