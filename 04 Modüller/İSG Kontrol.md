---
tip: modul
kod: "10.00.06"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# İSG Kontrol

> Kod `10.00.06` · [[10 İnşaat & Yapı]]

## Ne yapar
- SGP, KKD, ramak kala, belge süresi. Çekirdek genişleme: Personel & Vardiya.

## Özellikler
### MVP
- Süresi dolan İSG belgelerini listele
- Ramak kala aç
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Belge bitişinde yetki önerisi

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- İSG-KATİP ekranı

## Mevzuat
- 6331; Yapı İşlerinde İSG Yönetmeliği Doğrulama kapanışı: https://isgkatip.csgb.gov.tr/ bu turda 504 verdi. Açık API okunamadı. Kontrol listesi panelde, sözleşme bildirimi kullanıcıda kalır.

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
