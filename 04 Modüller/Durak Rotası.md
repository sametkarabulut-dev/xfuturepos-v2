---
tip: modul
kod: "12.04.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Durak Rotası

> Kod `12.04.01` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Çok duraklı teslim sırası; kurye gönderisi boyutu notu.

## Özellikler
### MVP
- Bugünkü 18 durağı sırala
- Öğleden sonra rotayı yeniden kur
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: sabah planı. İşlem: adres sırası taslağı. Çıktı: kurye listesi (onaylı).

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Google Routes API

## Mevzuat
- RG 15.05.2025: P kurye (≤30 kg / 300 dm³ tanımı). U-ETDS eşya zorunlu listesinde P yok. Google Routes API (Compute Routes / Route Matrix) kamuya açık dokümanda. Faturalı API anahtarı gerekir. P1 kurye tanımı ve U-ETDS listesinde P olmaması ayrı mevzuat notudur.

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
