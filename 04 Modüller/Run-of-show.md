---
tip: modul
kod: "16.00.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Run-of-show

> Kod `16.00.04` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- Etkinlik günü zaman akışı ve bağımlı kalemler.

## Özellikler
### MVP
- Kurulum penceresi çakışıyor mu?
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Brief saat değişiminde etkilenen ROS satırlarını işaretler.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yok / panel kaydı

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
