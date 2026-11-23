---
tip: modul
kod: "16.01.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Paket menü

> Kod `16.01.02` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- Kişi başı paket, ek hizmet ve toplam tutar.

## Özellikler
### MVP
- 250 kişi standart menü tutarı?
- Kokteyl paketine pasta ekle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Kişi değişince paket toplamını yeniler.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Kendi mutfakta gıda üretimi varsa işletme kayıt belgesi (16.06 ile aynı rejim).

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
