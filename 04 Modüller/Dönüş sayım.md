---
tip: modul
kod: "16.05.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Dönüş sayım

> Kod `16.05.03` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- Çıkış fişi ile dönüş sayımı; eksik/hasar.

## Özellikler
### MVP
- Dönüşte eksik ne?
- Hasar kaydı aç
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Fiş farkını kayıp/hasar satırına yazar (onay ister).

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
