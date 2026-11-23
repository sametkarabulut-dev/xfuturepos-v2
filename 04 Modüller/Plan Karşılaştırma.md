---
tip: modul
kod: "15.05.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Plan Karşılaştırma

> Kod `15.05.04` · [[15 Teknoloji Medya & Ajans]]

## Ne yapar
- Plan ile gerçekleşen maliyet/yerleşim sapması.

## Özellikler
### MVP
- Sapma olan mecraları göster
- Bütçe aşımını özetle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetik: dönem sonu. İşlem: plan ile gerçekleşeni karşılaştır. Çıktı: sapma tablosu.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Panel kaydı

## Mevzuat
- Küçük ofis TİAK aboneliği varsayılmadı. Doğrulama kapanışı: TİAK veya mecra ölçüm API’si varsayılmadı. Plan karşılaştırması paneldeki sipariş ve fatura satırından yapılır.

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
