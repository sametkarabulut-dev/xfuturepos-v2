---
tip: modul
kod: "16.04.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Gösteri dosya

> Kod `16.04.01` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- Sanatçı, rider, mekân/alan ve çağrı saatleri.

## Özellikler
### MVP
- Cuma teknik rider eksikleri?
- Sanatçı çağrı saati?
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Rider maddelerini teknik checklist'e aktarır.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- 5188 sayılı Kanun — geçici konser/sahne için özel güvenlik valilik izni dosya kalemi olabilir.

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
