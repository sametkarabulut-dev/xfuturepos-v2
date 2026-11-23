---
tip: modul
kod: "15.08.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Ürün Birikimi

> Kod `15.08.02` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Ürün backlog ve sürüm hedefi.

## Özellikler
### MVP
- Bir sonraki sürüme aday işleri seç
- Destekten ürüne çevrilecekleri bul
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: destek kapandı. İşlem: tekrarlayan talepleri kümele. Çıktı: backlog aday listesi.

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
