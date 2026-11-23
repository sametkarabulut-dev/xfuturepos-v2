---
tip: modul
kod: "10.06.04"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Oda Tescil

> Kod `10.06.04` · [[10 İnşaat & Yapı]]

## Ne yapar
- Büro tescil / UYDS hesap.

## Özellikler
### MVP
- Büro tescil bitişini hatırlat
- Müellif hesap durumu
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Vize takvimi

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- UYDS ve oda kaydı

## Mevzuat
- UYDS müellif başvurusu Doğrulama kapanışı: UYDS adresi 500 verdi. Meslek odası için tek açık API yok. Tescil tarihi elle tutulur.

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
