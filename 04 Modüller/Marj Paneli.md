---
tip: modul
kod: "12.06.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Marj Paneli

> Kod `12.06.05` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Alış navlun ile satış navlun farkı; zararlı iş uyarısı.

## Özellikler
### MVP
- Bu ay negatif marjlı işleri göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: iş kapandı. İşlem: marj < 0 ise uyarı. Çıktı: rapor satırı.

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
