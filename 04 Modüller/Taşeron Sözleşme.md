---
tip: modul
kod: "10.00.07"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Taşeron Sözleşme

> Kod `10.00.07` · [[10 İnşaat & Yapı]]

## Ne yapar
- Kapsam, birim fiyat, ölçüm, teminat, ek iş. Çekirdek genişleme: CRM.

## Özellikler
### MVP
- Yeni sıva taşeron sözleşmesi oluştur
- Ek iş protokollerini göster
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Sözleşmesiz başlangıç ve teminat vade uyarısı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- TBK / alt yüklenici sözleşmeleri

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
