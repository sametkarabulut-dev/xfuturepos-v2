---
tip: modul
kod: "12.01.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Sefer Planı

> Kod `12.01.01` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Güzergâh, yükleme-boşaltma penceresi ve araç-şoför ataması; boş dönüş notu.

## Özellikler
### MVP
- Yarınki 5 seferi planla
- 34 DEF 01 i bu sefere ata
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: sevkiyat onaylandı. İşlem: müsait araç-şoför öner. Çıktı: atama taslağı (onaylı).

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- K1: ticari yurt içi eşya taşımacılığı.

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
