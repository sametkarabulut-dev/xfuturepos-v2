---
tip: modul
kod: "15.01.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Ortam Envanteri

> Kod `15.01.04` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Müşteri ortamı, erişim ve sürüm kaydı.

## Özellikler
### MVP
- Müşteri ortam kartını özetle
- Eksik erişimleri listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: kurulum veya erişim değişti. İşlem: kartı güncelle. Çıktı: eksik erişim listesi.

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
