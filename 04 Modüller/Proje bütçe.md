---
tip: modul
kod: "16.03.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Proje bütçe

> Kod `16.03.01` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- Kurumsal brief, kalem bütçe ve onay kapıları.

## Özellikler
### MVP
- Lansman bütçe sapması?
- AV kalemi onaylı mı?
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Onaysız kaleme sipariş açmayı engeller.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Müzikli lansman/gala/kongrede MESAM-MSG 4.B/4.C; kimin lisans alacağı sözleşmede.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[16 Etkinlik & Organizasyon]]:** sektör/alt araç

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
