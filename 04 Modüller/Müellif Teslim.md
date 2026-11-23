---
tip: modul
kod: "10.06.03"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Müellif Teslim

> Kod `10.06.03` · [[10 İnşaat & Yapı]]

## Ne yapar
- YDK/idare teslim tutanağı.

## Özellikler
### MVP
- YDK’ye proje teslim et
- Bekleyen teslimler
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Teslim checklist

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- UYDS

## Mevzuat
- 4708 proje uygunluk Doğrulama kapanışı: https://uyds.csb.gov.tr/ bu turda 500 verdi. API dokümanı alınamadı. Teslim paketi panelde hazırlanır.

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
