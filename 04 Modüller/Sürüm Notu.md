---
tip: modul
kod: "15.08.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Sürüm Notu

> Kod `15.08.04` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Sürüm notu taslağı.

## Özellikler
### MVP
- Bu sürümün notunu yaz
- Kırıcı değişiklikleri işaretle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: sürüm etiketi. İşlem: birleşen işlerden not üret. Çıktı: sürüm notu taslağı.

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
