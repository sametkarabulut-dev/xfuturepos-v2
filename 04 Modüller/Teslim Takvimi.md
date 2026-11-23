---
tip: modul
kod: "15.00.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Teslim Takvimi

> Kod `15.00.04` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Teslim tarihleri, bağımlılıklar ve gecikme riski.

## Özellikler
### MVP
- Bu hafta gecikecek teslimleri listele
- Müşteri Y için teslim takvimini özetle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: sabah. İşlem: bitiş tarihi ile ilerlemeyi karşılaştır. Çıktı: riskli teslim listesi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yok / panel kaydı

## Yeniden kullanım
- **Araç türü:** ozel
- **[[15 Teknoloji Medya & Ajans]]:** sektör/alt araç

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
