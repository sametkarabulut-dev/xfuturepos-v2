---
tip: modul
kod: "09.01.05"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: hayir
gelistirme_suresi: "tahmin"
oncelik_modul: V2
zorunluluk: opsiyonel
---
# Piyasa Bandı

> Kod `09.01.05` · [[09 Emlak & Gayrimenkul]]

## Ne yapar
- Benzer ilanlardan bilgilendirme amaçlı fiyat bandı önerisi.

## Özellikler
### MVP
- Bu daire için fiyat bandı öner
- Son 30 gün benzer satılıkları özetle
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: fiyat güncelleme talebi → İşlem: band hesaplama → Çıktı: öneri + kaynak özeti (otomatik fiyat yazma yok)

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- sahibinden kurumsal aktarım (sözleşmeli)

## Mevzuat
- İlan platformu API erişimi kamuya açık doğrulanmadı. Doğrulama kapanışı: sahibinden.com API yardım yazısı açıldı. Aktarım, EİDS’e entegre ilancılık firmasına sözleşme ile verilir. Hepsiemlak için açık uç bu turda yok. Piyasa bandı elle girilir.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[09 Emlak & Gayrimenkul]]:** sektör/alt araç

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
