---
tip: modul
kod: "12.04.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Yoğunluk Paneli

> Kod `12.04.05` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Saat dilimine göre başarısız teslim ve neden özeti.

## Özellikler
### MVP
- Dün başarısız teslim nedenlerini özetle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: gün sonu. İşlem: neden dağılımı. Çıktı: rapor taslağı.

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
