---
tip: modul
kod: "09.05.06"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Dinamik Fiyat

> Kod `09.05.06` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Sezon ve doluluk bazlı fiyat bandı önerisi; yazma insan onaylı.

## Özellikler
### MVP
- Yarın için fiyat öner
- Düşük doluluk günlerini işaretle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: doluluk eşiği altı → İşlem: fiyat bandı önerisi → Çıktı: onay kuyruğu (otomatik fiyat yazılmaz)

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yanıltıcı tanıtım yaptırımları Yönetmelik değişiklikleriyle güçlendirildi.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[09 Emlak & Gayrimenkul]]:** sektör/alt araç

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
