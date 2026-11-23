---
tip: modul
kod: "10.02.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Ekip Dağılımı

> Kod `10.02.03` · [[10 İnşaat & Yapı]]

## Ne yapar
- Ekip-şantiye ataması. Çekirdek genişleme: Personel & Vardiya.

## Özellikler
### MVP
- Yarın 4 ustayı D şantiyesine kaydır
- Boşta kalan ekibi bul
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Çakışma engeli

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Panel kaydı

## Mevzuat
- Yetki belgeli usta / Şantiye-M Doğrulama kapanışı: Harici sistem yok. Ekip listesi panelin içinde.

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
