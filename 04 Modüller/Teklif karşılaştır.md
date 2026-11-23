---
tip: modul
kod: "16.02.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Teklif karşılaştır

> Kod `16.02.02` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- Aynı hizmet kalemine gelen teklif ve teyit durumu.

## Özellikler
### MVP
- Üç fotoğraf teklifini karşılaştır
- En ucuz ama teyitsiz kim?
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Teslim saati çakışan tedarikçileri gösterir.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Yok / panel kaydı

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
