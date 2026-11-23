---
tip: modul
kod: "13.05.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Kayıt Onay

> Kod `13.05.03` · [[13 Üretim & İmalat]]

## Ne yapar
- İşletme kayıt/onay belgesi hatırlatıcı; tam HACCP suite değil

## Özellikler
### MVP
- Kayıt belgesi bitiş tarihi
- Onay kapsamım ne
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Belge süresine 30 gün kala uyarı

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Gıda İşletmelerinin Kayıt ve Onay İşlemlerine Dair Yönetmelik

## Yeniden kullanım
- **Araç türü:** ozel
- **[[13 Üretim & İmalat]]:** sektör/alt araç

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
