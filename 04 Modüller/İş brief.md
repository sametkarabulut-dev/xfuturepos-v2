---
tip: modul
kod: "16.02.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# İş brief

> Kod `16.02.01` · [[16 Etkinlik & Organizasyon]]

## Ne yapar
- Mekânsız planlayıcı iş dosyası: brief, bütçe, karar sahibi.

## Özellikler
### MVP
- Kına brief'i özetle
- Bütçe tavanı aşıldı mı?
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Brief değişince tedarikçi kalemlerini yeniden etiketler.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- Telif/müzik yayın izni genelde mekânın; sözleşmede sorumluluk satırı tutulur.

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
