---
tip: modul
kod: "09.03.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Arıza Talep

> Kod `09.03.03` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Kat maliki/kiracı talep, teknisyen atama ve SLA.

## Özellikler
### MVP
- Acil arızaları listele
- Ortalama çözüm süresini göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: yeni talep → İşlem: öncelik skoru → Çıktı: atama önerisi

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- KMK m.35 yönetici görevleri çerçevesinde operasyon.

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
