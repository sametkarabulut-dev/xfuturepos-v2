---
tip: modul
kod: "15.03.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# SEO İşleri

> Kod `15.03.04` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- SEO iş listesi ve sayfa/anahtar kelime takibi.

## Özellikler
### MVP
- Bu ayın SEO işlerini özetle
- Yarım kalan sayfa işlerini listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: haftalık. İşlem: açık SEO kartlarını özetle. Çıktı: iş özeti.

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
