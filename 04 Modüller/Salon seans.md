---
tip: modul
kod: "16.01.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Salon seans

> Kod `16.01.01` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- Çoklu salon ve öğle/akşam seans rezervasyonu; sözün kayda bağlanması.

## Özellikler
### MVP
- Salon B 7 Haziran öğle?
- Bu hafta kesinleşenler?
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Kanal notunu takvimle karşılaştırıp çifte söz uyarır.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Panel seansı

## Mevzuat
- Doğrulama kapanışı: DüğünAsist, DavetPro, BaloSoft ve Ajandam için açık API bu turda yok. Seans panelde tutulur.

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
