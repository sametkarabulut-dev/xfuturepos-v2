---
tip: modul
kod: "09.04.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Rapor İş Akışı

> Kod `09.04.01` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Sipariş → saha → taslak → sorumlu imza → teslim pipeline'ı.

## Özellikler
### MVP
- İmzada bekleyen raporları getir
- Bu banka için SLA ihlallerini göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: aşama gecikmesi → İşlem: bottleneck uyarısı → Çıktı: sorumlu/uzman görev kartı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- SPK III-62.3; sorumlu değerleme uzmanı kontrol ve imza.

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
