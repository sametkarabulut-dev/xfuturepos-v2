---
tip: modul
kod: "10.04.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Keşif Randevu

> Kod `10.04.01` · [[10 İnşaat & Yapı]]

## Ne yapar
- Keşif randevusu; CRM genişlemesi.

## Özellikler
### MVP
- Yarın keşif randevusu koy
- Bu hafta keşifleri listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- No-show yeniden plan

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- Takvim

## Mevzuat
- Ruhsat ihtiyacı işe göre 3194

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
