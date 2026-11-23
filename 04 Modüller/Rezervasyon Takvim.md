---
tip: modul
kod: "09.05.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Rezervasyon Takvim

> Kod `09.05.01` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Kısa süreli konaklama takvimi, çakışma ve kapalı gün yönetimi.

## Özellikler
### MVP
- Bu hafta doluluk göster
- Çakışan rezervasyonları bul
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: yeni rezervasyon → İşlem: çakışma ve izin belgesi bayrağı kontrolü → Çıktı: onay/red önerisi

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- 7464 sayılı Kanun; tek seferde ≤100 gün turizm amaçlı kiralama.

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
