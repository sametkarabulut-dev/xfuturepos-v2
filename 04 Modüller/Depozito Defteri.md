---
tip: modul
kod: "09.02.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Depozito Defteri

> Kod `09.02.05` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Depozito alma, iade, mahsup ve belgelendirme.

## Özellikler
### MVP
- İade bekleyen depozitoları listele
- Mahsup kalemlerini özetle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: sözleşme bitişi → İşlem: iade/mahsup önerisi → Çıktı: onaylı ödeme talimatı taslağı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Teminat/depozito uygulamaları sözleşmeye bağlı.

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
