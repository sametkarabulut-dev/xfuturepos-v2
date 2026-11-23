---
tip: modul
kod: "13.03.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Dönüş İrsaliye

> Kod `13.03.03` · [[13 Üretim & İmalat]]

## Ne yapar
- Mamulün müşteriye sevki. Çekirdek genişleme: e-Fatura/e-Arşiv.

## Özellikler
### MVP
- Mamulü müşteriye sevk et
- İrsaliye hazırla
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Kabul sonrası e-irsaliye bayrağı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Mikro e-İrsaliye API

## Mevzuat
- Ciro 10M vs GTİP 72/73 ayrımı Doğrulama kapanışı: Mikro e-İrsaliye uçları açıldı. Dönüş irsaliyesi taslaktır, GİB gönderimi onayla.

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
