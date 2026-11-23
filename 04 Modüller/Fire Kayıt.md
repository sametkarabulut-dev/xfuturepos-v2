---
tip: modul
kod: "13.00.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Fire Kayıt

> Kod `13.00.03` · [[13 Üretim & İmalat]]

## Ne yapar
- İş emri bazlı fire; reçete toleransı ile gerçekleşen karşılaştırma

## Özellikler
### MVP
- İş emri 88 fire kaydet 12 adet
- Bu hafta fire aşımı
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Aşımı hesaplar ve onay kuyruğuna düşürür

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

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
