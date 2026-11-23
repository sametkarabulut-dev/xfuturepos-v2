---
tip: modul
kod: "10.01.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Ruhsat Takibi

> Kod `10.01.01` · [[10 İnşaat & Yapı]]

## Ne yapar
- Ruhsat-iskan evrak ve adım takibi.

## Özellikler
### MVP
- Ruhsat bekleyen projeleri göster
- İskan evrak listesini çıkar
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Eksik evrak hatırlatması

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- İdare ekranı

## Mevzuat
- 3194 İmar Doğrulama kapanışı: Tek ulusal belediye e-başvuru API’si yok. Ruhsat evrakı panelde toplanır, başvuru ilgili idarenin ekranında kalır.

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
