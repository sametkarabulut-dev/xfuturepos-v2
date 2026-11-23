---
tip: modul
kod: "09.04.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Emsal Analizi

> Kod `09.04.04` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Karşılaştırılabilir satış/kira emsal tablosu ve düzeltme önerileri.

## Özellikler
### MVP
- 3 emsal öner
- Düzeltme katsayılarını özetle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: taslak aşaması → İşlem: emsal öneri tablosu → Çıktı: uzman inceleme paneli (rapora otomatik yazılmaz)

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Nihai değer ve rapor içeriği lisanslı uzman sorumluluğunda.

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
