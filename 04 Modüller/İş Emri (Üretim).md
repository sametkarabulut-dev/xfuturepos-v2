---
tip: modul
kod: "13.00.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# İş Emri (Üretim)

> Kod `13.00.01` · [[13 Üretim & İmalat]]

## Ne yapar
- Sipariş veya stok ihtiyacından iş emri; durum akışı; tam MES değil

## Özellikler
### MVP
- Sipariş 452 için iş emri aç
- Geciken iş emirlerini listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Termin aşımına 24 saat kala uyarı; kapanışta reçete tüketim önerisi

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Mikro API (doğrulandı), Logo/Nebim (dogrulanmali)

## Mevzuat
- Yok / panel kaydı

## Yeniden kullanım
- **Araç türü:** ozel
- **[[13 Üretim & İmalat]]:** sektör/alt araç

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
