---
tip: modul
kod: "09.02.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Bakım İş Emri

> Kod `09.02.03` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Kiracı/malik arıza kaydı, tedarikçi atama ve kapanış.

## Özellikler
### MVP
- Açık arızaları önceliklendir
- Bu ay bakım maliyetini özetle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: yeni arıza → İşlem: kategori/öncelik önerisi → Çıktı: atama önerisi kartı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yok / panel kaydı

## Yeniden kullanım
- **Araç türü:** ozel
- **[[09 Emlak & Gayrimenkul]]:** sektör/alt araç

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
