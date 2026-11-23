---
tip: modul
kod: "13.05.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Lot İzle

> Kod `13.05.01` · [[13 Üretim & İmalat]]

## Ne yapar
- Girdi-üretim-satış one-up/one-down izlenebilirlik

## Özellikler
### MVP
- Lot G-90 nereye gitti
- Bu satışın hammaddesi
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Satışta lot zorunluluğu; geri çağırma listesi

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- 13.02.02

## Mevzuat
- 5996 m.24; Gıda ve Yemin Resmi Kontrollerine Dair Yönetmelik m.39

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
