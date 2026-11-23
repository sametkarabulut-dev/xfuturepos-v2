---
tip: modul
kod: "12.03.02"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Hat Seferi

> Kod `12.03.02` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Hat aracı kalkış, doluluk ve varış ambarında aktarma.

## Özellikler
### MVP
- İstanbul Ankara hattı doluluk oranı
- Hat 3 ü kalkışa kapat
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: kalkışa 2 saat. İşlem: U-ETDS taslak + eksik yük uyarısı. Çıktı: onay kuyruğu.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- U-ETDS eşya SOAP

## Mevzuat
- N türü için U-ETDS eşya bildirimi zorunlu.

## Yeniden kullanım
- **Araç türü:** ozel
- **[[12 Lojistik & Taşımacılık]]:** sektör/alt araç

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
