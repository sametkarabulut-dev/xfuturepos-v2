---
tip: modul
kod: "12.06.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Multimodal Plan

> Kod `12.06.04` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Kara + deniz/hava bacak checklisti.

## Özellikler
### MVP
- Mersin liman bacağını plana ekle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: liman ETA. İşlem: sonraki bacak hatırlatması. Çıktı: plan kartı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Hat planı

## Mevzuat
- TİO kombine/intermodal faaliyet tanımı. Doğrulama kapanışı: Seçili liman veya hat yok. Plan elle tutulur.

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
