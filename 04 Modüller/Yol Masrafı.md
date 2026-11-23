---
tip: modul
kod: "12.01.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Yol Masrafı

> Kod `12.01.03` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Mazot, köprü, bekleme masraflarını sefere bağlayıp kârlılık taslağı üretir.

## Özellikler
### MVP
- Sefer 12 ye 2500 TL mazot ekle
- Bu haftanın mazot toplamını söyle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: sefer kapandı. İşlem: masraf satırı yoksa hatırlat. Çıktı: eksik masraf listesi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yok / panel kaydı

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
