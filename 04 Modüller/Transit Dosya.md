---
tip: modul
kod: "12.02.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Transit Dosya

> Kod `12.02.03` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- TIR karne / NCTS / geçiş izni checklist; hangisinin kullanılacağı güzergâha bağlı.

## Özellikler
### MVP
- Bu seferde TIR karne durumu ne
- Almanya geçiş izni eksik mi
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: sefer gümrük öncesi. İşlem: eksik transit belgesi listesi. Çıktı: checklist.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- TOBB TIR portalı

## Mevzuat
- TIR gümrük transit; CMR sözleşme belgesi. AB içi transitte NCTS yaygın. Doğrulama kapanışı: https://tir.tobb.org.tr/ bu turda 500 verdi. Portal API’si okunamadı. Evrak listesi panelde.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[12 Lojistik & Taşımacılık]]:** sektör/alt araç

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
