---
tip: modul
kod: "16.05.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Ekipman çıkış

> Kod `16.05.01` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- Ekipman parkı, işe çıkış fişi ve rezervasyon kilidi.

## Özellikler
### MVP
- 2x line array müsait mi?
- Cumartesi çıkış listesi
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Çifte rezervasyonda ekipmanı kilitler.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- MSG/MESAM ve gıda kaydı uygulanmaz.

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
