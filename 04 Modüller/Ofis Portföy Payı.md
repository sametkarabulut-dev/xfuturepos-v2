---
tip: modul
kod: "09.01.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Ofis Portföy Payı

> Kod `09.01.04` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Şube/franchise arası portföy görünürlük ve komisyon paylaşım kuralları.

## Özellikler
### MVP
- Ortak portföyleri listele
- Paylaşım kuralını özetle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: paylaşıma açma → İşlem: kural uygunluk kontrolü → Çıktı: onay bekleyen paylaşım kaydı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Sözleşmeli işletme ilişkisi Taşınmaz Ticareti Yönetmeliği çerçevesinde.

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
