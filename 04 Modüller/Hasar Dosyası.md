---
tip: modul
kod: "12.00.06"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Hasar Dosyası

> Kod `12.00.06` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Hasar/kayıp dosyası, tutanak ve sigorta iletim checklisti; tazminat ödemesi AI onayı olmadan yok.

## Özellikler
### MVP
- Sevkiyat 441 için hasar dosyası aç
- Açık hasar dosyalarını özetle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: POD hasarlı. İşlem: dosya + foto checklist oluştur. Çıktı: operatör onay kartı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yurt içi TTK; uluslararası CMR sorumluluk rejimi. Ev eşyası CMR kapsamı dışı.

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
