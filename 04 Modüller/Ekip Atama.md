---
tip: modul
kod: "12.05.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Ekip Atama

> Kod `12.05.03` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Taşınma günü kamyon, ekip ve paketleme malzemesi ataması.

## Özellikler
### MVP
- 15 Mayıs taşınmasına 3 kişi ata
- Paketleme malzemesi eksiği var mı
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: kapora alındı. İşlem: müsait ekip öner. Çıktı: onaylı atama.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- K3 yurt içi, C3 yurt içi+uluslararası taşınma; U-ETDS K3/C3.

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
