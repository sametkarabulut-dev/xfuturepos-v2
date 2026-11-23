---
tip: modul
kod: "16.05.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Kurulum pencere

> Kod `16.05.02` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- Load-in/out pencereleri ve ekip çağrısı.

## Özellikler
### MVP
- Load-in 14–18 çakışıyor mu?
- Kaç teknisyen?
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Örtüşen kurulum pencerelerinde uyarır.

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
