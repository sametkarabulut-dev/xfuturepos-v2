---
tip: modul
kod: "09.03.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Ortak Alan

> Kod `09.03.04` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Ortak alan (salon, misafir otopark vb.) rezervasyon yönetimi.

## Özellikler
### MVP
- Cumartesi salon müsaitliğini göster
- Çakışan rezervasyonları bul
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: rezervasyon talebi → İşlem: çakışma kontrolü → Çıktı: onay bekleyen kayıt

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yönetim planı hükümlerine bağlı.

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
