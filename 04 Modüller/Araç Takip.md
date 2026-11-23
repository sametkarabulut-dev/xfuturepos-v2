---
tip: modul
kod: "12.00.07"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Araç Takip

> Kod `12.00.07` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Harici filo takip konumunu sevkiyata bağlar; marka API iddiası doğrulanmadan bağlanır.

## Özellikler
### MVP
- 34 ABC 123 son bilinen konum
- ETA sı geciken araçları göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: ETA aşıldı. İşlem: konum yoksa manuel ETA iste. Çıktı: gecikme uyarısı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Elle veya CSV konum

## Mevzuat
- Doğrulama kapanışı: Seçili filo markası yok. Konum elle veya CSV ile girilir.

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
