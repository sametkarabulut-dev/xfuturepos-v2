---
tip: modul
kod: "16.06.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Menü maliyet

> Kod `16.06.01` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- Reçete, kişi başı maliyet ve teklif.

## Özellikler
### MVP
- 220 kişilik menü maliyeti?
- Vejetaryen 30 kişi ekle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Kişi Δ → üretim miktarı ve maliyet.

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
