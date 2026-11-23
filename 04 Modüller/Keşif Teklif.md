---
tip: modul
kod: "10.01.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Keşif Teklif

> Kod `10.01.05` · [[10 İnşaat & Yapı]]

## Ne yapar
- Birim fiyatlı teklif.

## Özellikler
### MVP
- Villaya teklif hazırla
- Teklifi sözleşmeye çevir
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Onaydan proje kartı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yok / panel kaydı

## Yeniden kullanım
- **Araç türü:** ozel
- **[[10 İnşaat & Yapı]]:** sektör/alt araç

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
