---
tip: modul
kod: "15.04.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Varlık Sürümü

> Kod `15.04.01` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Dosya sürümü, final ve müşteri klasörü.

## Özellikler
### MVP
- Final sürümü bul
- Eski sürümleri arşiv öner
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: yeni dosya. İşlem: sürüm etiketle. Çıktı: güncel final listesi.

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
