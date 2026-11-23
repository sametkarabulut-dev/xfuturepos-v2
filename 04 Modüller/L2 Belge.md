---
tip: modul
kod: "12.02.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# L2 Belge

> Kod `12.02.02` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- L2 yetki ve taşıt belgesi takibi; U-ETDS L2 yükümlülüğü.

## Özellikler
### MVP
- L2 geçerlilik tarihini göster
- Taşıt belgesine eklenecek plakalar
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: L2 bitişine 45 gün. İşlem: yönetici uyarısı. Çıktı: yenileme kartı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- RG 14.01.2023: C2 verilmiyor, mevcutlar L2. U-ETDS L2 zorunlu.

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
