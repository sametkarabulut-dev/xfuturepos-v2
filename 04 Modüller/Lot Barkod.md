---
tip: modul
kod: "13.02.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Lot Barkod

> Kod `13.02.02` · [[13 Üretim & İmalat]]

## Ne yapar
- Parti/lot kodu üretimi ve sevk bağlama

## Özellikler
### MVP
- Lot L-2411 oluştur
- Lot L-2411 nereye gitti
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- WO kapanışında lot üretimi

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Barkod yazıcı

## Mevzuat
- GTİP 72/73 sevklerinde lot satırı faydalı

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
