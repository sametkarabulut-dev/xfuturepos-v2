---
tip: modul
kod: "13.03.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Kapasite Slot

> Kod `13.03.05` · [[13 Üretim & İmalat]]

## Ne yapar
- Haftalık iş kabul slotları

## Özellikler
### MVP
- Perşembe boş slot
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Aşırı dolulukta yeni iş reddi önerisi

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
