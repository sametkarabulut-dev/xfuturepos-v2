---
tip: modul
kod: "12.03.01"
durum: tamamlandi
katman: sektorel
arac_turu: ozel
mvp: evet
gelistirme_suresi: "tahmin"
oncelik_modul: MVP
zorunluluk: zorunlu
---
# Parsiyel Toplama

> Kod `12.03.01` · [[12 Lojistik & Taşımacılık]]

## Ne yapar
- Parça yük kabul, etiketleme ve hat aracına konsolidasyon.

## Özellikler
### MVP
- Ankara hattına 4 parça ekle
- Bugün kabul edilen parçaları listele
### Sonraki sürüm
- Arşivdeki V2/opsiyonel genişlemeler

## AI otomasyonu
- Tetikleyici: ambar kabulü. İşlem: hedef hat öner. Çıktı: tasnif listesi.

## Çözdüğü ihtiyaçlar
- Sektör ortak ihtiyaç tablosuna bak

## Entegrasyonlar
- yok

## Mevzuat
- N1 il içi, N2 iller arası nakliyat ambarı; U-ETDS N1/N2.

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
