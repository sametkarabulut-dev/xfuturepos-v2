---
tip: modul
kod: "13.06.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Fasoncu Sevk

> Kod `13.06.01` · [[13 Üretim & İmalat]]

## Ne yapar
- Fasoncuya malzeme sevk ve iş emri bağlama

## Özellikler
### MVP
- ABC'ye 405 kg kumaş sevk et
- Açık sevkler
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Reçeteden gönderilecek miktar hesabı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Mikro e-İrsaliye API

## Mevzuat
- Sevk irsaliyesi; e-irsaliye ciro/GTİP bayrağı Doğrulama kapanışı: Mikro e-İrsaliye uçları açıldı. Fasonda malzeme çıkışı taslaktır, gönderim onayla.

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
