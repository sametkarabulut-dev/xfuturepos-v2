---
tip: modul
kod: "12.06.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Booking Emri

> Kod `12.06.02` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Müşteri emrini taşıyıcı iş emrine çevirir; alış/satış navlun marjı tutar.

## Özellikler
### MVP
- Booking 220 yi Ahmet Lojistik e ver
- Açık bookingleri listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: müşteri onayı. İşlem: iş emri taslağı. Çıktı: taşıyıcıya gönderim onayı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- U-ETDS fiili taşımayı yapan yetki belgesi sahibinde; salt TİO eşya listesinde yok.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[12 Lojistik & Taşımacılık]]:** sektör/alt araç

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
