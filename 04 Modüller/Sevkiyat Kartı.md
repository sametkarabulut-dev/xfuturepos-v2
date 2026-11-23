---
tip: modul
kod: "12.00.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Sevkiyat Kartı

> Kod `12.00.01` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Yük/sevkiyat yaşam döngüsü: talep, yükleme, yolda, teslim; gönderici/alıcı, tonaj ve adres tek kartta.

## Özellikler
### MVP
- Bugün yüklenen 3 sevkiyatı listele
- ABC Ltd sevkiyatını yolda yap
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: planlanan teslim +2 saat geçti. İşlem: durumu teslim bekliyor yapıp operatöre kart aç. Çıktı: onay/erteleme seçenekli uyarı.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Taşıma ilişkisi TTK; uluslararasıda CMR. Belge türü alt sektöre göre.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[12 Lojistik & Taşımacılık]]:** sektör/alt araç

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
