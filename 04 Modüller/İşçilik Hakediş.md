---
tip: modul
kod: "13.03.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# İşçilik Hakediş

> Kod `13.03.02` · [[13 Üretim & İmalat]]

## Ne yapar
- Kabul adedi üzerinden işçilik faturalama. Çekirdek genişleme: e-Fatura/e-Arşiv.

## Özellikler
### MVP
- Müşteri Y bu ay hakediş
- Birim fiyat 4,5 TL
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Dönem sonu hakedişten e-Fatura önerisi

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- e-Fatura

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
