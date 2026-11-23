---
tip: modul
kod: "13.06.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Hakediş Kesinti

> Kod `13.06.03` · [[13 Üretim & İmalat]]

## Ne yapar
- Fire/eksik/ret kesintili fasoncu ödemesi. Çekirdek genişleme: Muhasebe & Gelir-Gider.

## Özellikler
### MVP
- ABC hakedişini kesintili hesapla
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Aşım bedelini hakedişten düşer; fatura eşleştirir

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- e-Fatura, Muhasebe

## Mevzuat
- Yok / panel kaydı

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
