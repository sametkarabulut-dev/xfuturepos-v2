---
tip: modul
kod: "12.03.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Ambar Stok

> Kod `12.03.03` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Kapalı ambar giriş-çıkış, göz/yer ve bekleyen parça arama.

## Özellikler
### MVP
- Raf A-12 de ne var
- 3 gündür bekleyen parçalar
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: bekleme 72 saati aştı. İşlem: müşteri arama listesi. Çıktı: operatör kartı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- N1 ≥75 m², N2 ≥150 m² kapalı ambar şartı (KTY md.14).

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
