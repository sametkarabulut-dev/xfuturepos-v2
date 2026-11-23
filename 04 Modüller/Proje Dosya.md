---
tip: modul
kod: "10.06.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Proje Dosya

> Kod `10.06.01` · [[10 İnşaat & Yapı]]

## Ne yapar
- Disiplin dosya ağacı.

## Özellikler
### MVP
- Statik son sürümü aç
- Paylaşılan linki kapat
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Eksik disiplin uyarısı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Bulut depolama

## Mevzuat
- Müellif sorumluluğu

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
