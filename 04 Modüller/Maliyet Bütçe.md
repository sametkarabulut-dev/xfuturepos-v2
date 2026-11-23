---
tip: modul
kod: "10.01.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Maliyet Bütçe

> Kod `10.01.03` · [[10 İnşaat & Yapı]]

## Ne yapar
- Keşif vs gerçekleşen. Çekirdek genişleme: Muhasebe.

## Özellikler
### MVP
- Bu ay bütçe sapmasını göster
- Demir kalemini artır
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Sapma eşiği uyarısı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yok / panel kaydı

## Yeniden kullanım
- **Araç türü:** ozel
- **[[10 İnşaat & Yapı]]:** sektör/alt araç

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
