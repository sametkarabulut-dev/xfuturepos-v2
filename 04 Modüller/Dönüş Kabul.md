---
tip: modul
kod: "13.06.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Dönüş Kabul

> Kod `13.06.02` · [[13 Üretim & İmalat]]

## Ne yapar
- Mamul kabul/ret ve reçete tüketim düşümü

## Özellikler
### MVP
- ABC dönüşünü kaydet 960 adet
- Ret 40
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Bakiye = sevk − (kabul×reçete) − fire

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- 13.00.03, 13.00.05

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
