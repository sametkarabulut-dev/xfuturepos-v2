---
tip: modul
kod: "13.05.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Soğuk Kayıt

> Kod `13.05.04` · [[13 Üretim & İmalat]]

## Ne yapar
- Basit sıcaklık/ölçüm günlüğü

## Özellikler
### MVP
- Soğuk oda bugün kaydı
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Eksik günlük kayıt hatırlatması

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Elle sıcaklık

## Mevzuat
- Resmi kontrol cihaz ölçüm kayıtları Doğrulama kapanışı: Seçili sensör markası yok. Sıcaklık elle girilir.

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
